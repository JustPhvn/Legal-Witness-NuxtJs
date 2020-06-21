<template>
  <div>
    <b-container>
      <b-jumbotron>
        <template v-slot:header>Legal Expert Witness</template>

        <template v-slot:lead>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat, ut
          quibusdam ratione esse maiores cum nisi odio? Accusantium ad provident
          porro illum magnam aliquid modi eos placeat quaerat mollitia. Minima?
        </template>

        <hr class="my-4" />

        <p>
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Magni labore
          voluptates alias natus voluptatem dolore ipsum, placeat ea numquam.
          Maxime consectetur nostrum in dolorum similique sit, mollitia fuga
          suscipit magni?
        </p>

        <b-button v-b-modal.modal-1>Contact</b-button>

        <b-modal id="modal-1" title="Contact">
          <p class="my-4">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus
            minima architecto consequuntur neque culpa tempora reiciendis,
            distinctio numquam aperiam adipisci eaque et nobis non saepe iusto
            cumque. Mollitia, nemo nostrum?
          </p>
        </b-modal>
      </b-jumbotron>
    </b-container>
  </div>
</template>

<script>
export default {}
</script>

<style></style>
