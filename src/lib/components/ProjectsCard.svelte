<script lang="ts">
    import { Button } from "./ui/button";

    export let title: string;
    export let subtitle: string;
    export let imgSrc: string;
</script>

<div
    class="bg-secondary text-secondary-foreground shadow-xl flex flex-col sm:flex-row gap-4 justify-between"
>
    <div class="flex flex-col gap-8 pt-8">
        <div class="flex flex-col min-w-32 border-s-8 border-primary ps-8">
            <span class="font-bold text-primary text-xl"> {title}</span>
            <span> {subtitle}</span>
        </div>

        <div class="ps-8 pb-8">
            <slot />
            
        </div>
    </div>
    <img src={imgSrc} alt="صورة المشروع" class="w-auto sm:w-64 object-cover" />
</div>
