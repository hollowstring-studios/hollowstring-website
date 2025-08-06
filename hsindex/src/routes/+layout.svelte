<script lang="ts">
	import '../app.css';
	import favicon from '$lib/assets/favicon.ico';
  import logo from '$lib/assets/logo.png';
	import { Navbar, NavBrand, NavLi, NavUl, NavHamburger } from "flowbite-svelte";
  import { Footer, FooterCopyright, FooterLinkGroup, FooterLink } from "flowbite-svelte";
	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<Navbar>
  <NavBrand href="/">
    <img src={logo} class="me-3 h-6 sm:h-9" alt="logo" />
    <span class="self-center text-xl font-semibold whitespace-nowrap dark:text-white">Hollowstring</span>
  </NavBrand>
  <NavHamburger />
  <NavUl>
    <NavLi href="/">Home</NavLi>
    <NavLi href="/projects">Projects</NavLi>
    <NavLi href="/about">About</NavLi>
    <NavLi href="/contact">Contact</NavLi>
  </NavUl>
</Navbar>

<main class="container mx-auto px-4 py-8">
	{@render children?.()}
</main>

<Footer>
<FooterCopyright href="/" by="Hollowstring Studios" year={2025} class="w-full"/>
</Footer>