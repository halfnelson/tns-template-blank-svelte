<page>
    <actionBar title="Svelte Native App" />
    <gridLayout>
        <label class="info" horizontalAlignment="center" verticalAlignment="center">
            <formattedString>
                <span class="far" text="&#xf135;" />
                <span text="{message}" />
            </formattedString>
        </label>
    </gridLayout>
</page>

<script>
    let message = "Blank Svelte Native app"
</script>

<style>
    .far {
        color: #3A53FF;
    }

    .info {
        font-size: 20;
    }
</style>