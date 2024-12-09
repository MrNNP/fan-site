<script>
	import Button from "$lib/button.svelte";
    const classData = "p-2 py-20 m-1 rounded-3xl shadow-lg h-max";
</script>
<div class="grid grid-rows-3 grid-cols-2  justify-center items-stretch justify-items-stretch p-11 h-max text-white text-3xl md:text-9xl text-center w-full rounded-lg">
    <span hidden class=""/>
    <Button classData={classData+" col-span-2"} path="Power" color="bg-black"/> 
    <Button classData={classData} path="Speed" color="bg-black"/>
    <Button classData={classData} path="Rotation" color="bg-black"/>
    <Button classData={classData} path="Sleep" color="bg-black"/>
    <Button classData={classData} path="Timer" color="bg-black"/>
    
</div>
<!-- <img src="/0001-0097.gif" class=""/> -->