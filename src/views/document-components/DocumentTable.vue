<template>
  <div class="table-responsive">
    <table class="table v-middle text-nowrap bg-transparent">
      <thead class="bg-light">
        <tr class>
          <th class="border-0">Name</th>
          <th class="border-0">Status</th>
          <th class="border-0">Owner</th>
          <th class="border-0">Last Edit</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>
            <div class="d-flex align-items-center">
              <div class>
                <h5 class="mb-0">John Admin</h5>
              </div>
            </div>
          </td>
          <td>
            <b-badge variant="danger" class="rounded-0">Draft</b-badge>
          </td>
          <td>John Doe</td>
          <td>19 Sept - me</td>
        </tr>
        <tr>
          <td>
            <div class="d-flex align-items-center">
              <div class>
                <h5 class="mb-0">John Doe</h5>
              </div>
            </div>
          </td>
          <td>
            <b-badge variant="info" class="rounded-0">Done</b-badge>
          </td>
          <td>John Doe</td>
          <td>19 Sept - me</td>
        </tr>
        <tr>
          <td>
            <div class="d-flex align-items-center">
              <div class>
                <h5 class="mb-0">John Admin</h5>
              </div>
            </div>
          </td>
          <td>
            <b-badge variant="success" class="rounded-0">Approve</b-badge>
          </td>
          <td>John Doe</td>
          <td>19 Sept - me</td>
        </tr>
        <tr>
          <td>
            <div class="d-flex align-items-center">
              <div class>
                <h5 class="mb-0">John Admin</h5>
              </div>
            </div>
          </td>
          <td>
            <b-badge variant="warning" class="rounded-0">Sign</b-badge>
          </td>
          <td>John Doe</td>
          <td>19 Sept - me</td>
        </tr>
        <tr>
          <td>
            <div class="d-flex align-items-center">
              <div class>
                <h5 class="mb-0">John Admin</h5>
              </div>
            </div>
          </td>
          <td>
            <b-badge variant="success" class="rounded-0">Approve</b-badge>
          </td>
          <td>John Doe</td>
          <td>19 Sept - me</td>
        </tr>

      </tbody>
    </table>
  </div>
</template>

<script>

export default {
	name:"DocumentTable",
    components: {}
}    
</script>