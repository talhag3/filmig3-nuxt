<template>
    <div class="flex h-full">
        <AppHeader v-if="$device.isMobileOrTablet"/>
        <AppSideBar v-else/>    
        <main :class="`w-full px-3 flex-1 ${$device.isMobileOrTablet ? '': 'ml-60'} h-full`">
            <slot />
        </main>
    </div>
</template>