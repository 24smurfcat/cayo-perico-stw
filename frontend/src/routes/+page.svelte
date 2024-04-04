<script>
    import { Wheel } from "svelte-custom-roulette";

    const items = [
        "Longfin",
        "Kosatka",
        "Alkonost",
        "Velum",
        "Annihilator",
        "Patrol Boat",
    ]
</script>

<Wheel
    {items}
    size={600}
    textColor="black"
    pointerColor="purple"
    pointerSize={60}
/>