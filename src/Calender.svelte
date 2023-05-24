<script>
  import {Datepicker, InlineCalendar } from "svelte-calendar";
  const theme = {
		calendar: {
			width: '600px',
			shadow: '0px 0px 5px rgba(0, 0, 0, 0.25)'
		}
	};
</script>

<main>
  <h1>Calender App</h1>
  <InlineCalendar {theme} />
  
</main>
<p>
    <Datepicker />
</p>

<style>
    p{
        
        padding: 5px;
    }
</style>
