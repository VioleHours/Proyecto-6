<script>
	import Header from "./components/Header.svelte";
	import Dashboard from "./components/Dashboard.svelte";
	let notes = [
    {
      id: 0,
      title: "Vacations",
      color: "yellow",
      text: "Hello!",
    },
    {
      id: 1,
      title: "Vacations",
      color: "red",
      text: "Hello!",
    },
  ];
  let copyNotes = [...notes];
  let count = notes.length;
</script>

<main>
  <Header />
  <div>{count} notes</div>
  <Dashboard notes={notes} />
</main>

<style>
</style>
