<script>
    import Nav from './components/nav.svelte';
    import Button from './components/Button.svelte';
    let menuItems = [
        { link: '#', name: 'Docs' },
        { link: '#', name: 'Home' },
        { link: '#', name: 'Blog' },
    ];
    test error
</script>

<Nav {menuItems} />
<Button text="Something" />
