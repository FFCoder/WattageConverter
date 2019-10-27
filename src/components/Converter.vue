<template>
    <div class="converterComponent">
        <b-form>
            <b-form-group
                id="wattageInput"
                label="Watts"
                label-for="watts-input"
                description="Input Watts Here">
            <b-form-input
                id="watts-input"
                v-model="watts"
                type="text"
                required
                aria-placeholder="Enter Watts">
            </b-form-input>

            </b-form-group>
        </b-form>

        {{ (watts / 120).toFixed(2) }} Amps
    </div>
</template>
<script>
export default {
  data: () => {
    return {
      watts: ''
    }
  }
}
</script>
<style lang="sass" scoped>
.converterComponent
    width: 50vw
    margin: auto
    padding: 2%
</style>
