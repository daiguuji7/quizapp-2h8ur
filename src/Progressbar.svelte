<script>
    export let maxTime;
    export let time;
</script>

<div class="w-full h-5 bg-orange-200">
    <div class="h-full rounded-md bh-orange-400" style="width: {`${time/maxTime*100}%`}"></div>
</div>