<template>
  <container>
    <row>
      <column md="8" class="mx-auto">
        <jumbotron class="mt-5">
          <h1 class="pb-2"><Fa icon="code" class="grey-text mr-2" />Advanced</h1>
          <h6 class="my-3">FREE</h6>
          <list-group>
            <!-- FREE -->
            <navbar-item class="list-group-item list-group-item-action" router href="/advanced/carousel">
              <h5 class="justify-content-between d-flex align-items-center">
                Carousel<fa icon="angle-right"/>
              </h5>
            </navbar-item>
            <navbar-item class="list-group-item list-group-item-action" router href="/advanced/chart">
              <h5 class="justify-content-between d-flex align-items-center">
                Charts<fa icon="angle-right"/>
              </h5>
            </navbar-item>
            <navbar-item class="list-group-item list-group-item-action" router href="/advanced/collapse">
              <h5 class="justify-content-between d-flex align-items-center">
                Collapse<fa icon="angle-right"/>
              </h5>
            </navbar-item>


            <navbar-item class="list-group-item list-group-item-action" router href="/advanced/popover">
              <h5 class="justify-content-between d-flex align-items-center">
                Popover<fa icon="angle-right"/>
              </h5>
            </navbar-item>
            <navbar-item class="list-group-item list-group-item-action" router href="/advanced/tooltip">
              <h5 class="justify-content-between d-flex align-items-center">
                Tooltip<fa icon="angle-right"/>
              </h5>
            </navbar-item>
            <navbar-item class="list-group-item list-group-item-action" router href="/advanced/videocarousel">
              <h5 class="justify-content-between d-flex align-items-center">
                Video Carousel<fa icon="angle-right"/>
              </h5>
            </navbar-item>
          </list-group>
        </jumbotron>
      </column>
    </row>
  </container>
</template>

<script>
import { Container, Row, Column, Fa, Jumbotron, NavbarItem, ListGroup } from 'mdbvue';

export default {
  name: 'AdvancedPage',
  components: {
    Container,
    Row,
    Column,
    Fa,
    Jumbotron,
    NavbarItem,
    ListGroup
  }
};
</script>

<style scoped>
.example-components-list {
  padding-top: 20px;
}

.example-components-list li {
  padding: 10px;
  background-color: white;
  border-bottom: 1px solid #f7f7f7;
  transition: .3s;
}

.example-components-list h6 {
  padding: 20px 10px 5px 10px;
  color: grey;
}

.example-components-list li:hover {
  background-color: #fafafa;
}

.example-components-list i {
  float: right;
  padding-top: 3px;
}

.nav-link.navbar-link h5 {
  color: #212529;
}
</style>
