<template>
    <div class="flex flex-col items-center justify-center h-screen bg-gray-100 dark:bg-gray-900 transition-colors duration-500">
        <div class="text-center">
            <h1 class="text-4xl font-extrabold text-gray-900 dark:text-gray-100 mb-4 transition-colors duration-500">
                敬请期待
            </h1>
            <p class="text-lg text-gray-600 dark:text-gray-400 mb-8 transition-colors duration-500">
                当我们发布足够多的项目时，xuehang.org 就会启动。
            </p>
            <div class="flex space-x-4 justify-center">
                <a href="https://github.com/xuehang-org" class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline transition-colors duration-300">
                    了解更多
                </a>
                <a href="https://x.com/xuehang_org" class="bg-green-500 hover:bg-green-700 text-white font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline transition-colors duration-300">
                    联系我们
                </a>
            </div>

            <div class="mt-8">
                <p class="text-sm text-gray-500 dark:text-gray-500 transition-colors duration-500">
                    © 2024 xuehang.org. 版权所有.
                </p>
            </div>
        </div>
    </div>
</template>

<script setup lang="ts">
// 这里可以添加一些逻辑，例如：
// - 获取配置信息
// - 设置页面标题
// - 预加载资源
// - 统计访问量
import { onMounted } from 'vue';

onMounted(() => {
    document.title = '敬请期待 - xuehang.org';
});
</script>