<template>
  <div>
    <b-card class="mb-4" no-body>
      <b-card-body>
        <h4 class="card-title">Document</h4>
      </b-card-body>
      <DocumentTable />
    </b-card>
  </div>
</template>

<script>
import DocumentTable from "./document-components/DocumentTable";
export default {
  name: "Starter",
  data: () => ({}),
  components: {
    DocumentTable,
  },
};
</script>
