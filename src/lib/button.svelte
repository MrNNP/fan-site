<script lang="ts">
    export let path: string;
    export let classData: string;
    export let color: string;
</script>
<!-- svelte-ignore a11y_click_events_have_key_events -->
<!-- svelte-ignore a11y_no_static_element_interactions -->
<div on:click={()=>fetch("http://group27Fan.resource.campus.njit.edu/"+path.toLowerCase()+"button", {
    mode: "no-cors",
})}
class={classData + " " + color}
>{path}</div>