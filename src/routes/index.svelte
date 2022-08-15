<script>
    import TodoItem from "$lib/todo-item.svelte";
    const title = 'Todo'
    
</script>

<svelte:head>
    <title>{title}</title>
</svelte:head>

<h1>{title}</h1>
<form action="">
    <input type="text" name="text" placeholder="+ type to add a todo">
</form>

<TodoItem />
<TodoItem />
<TodoItem />