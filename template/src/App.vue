<template>
  <div id="app">

    <!-- Statusbar -->
    <f7-statusbar></f7-statusbar>

    <f7-views>
      <f7-view main>
        <f7-pages>
          <f7-page navbar-through>
            <f7-navbar>
              <f7-nav-center>{{ name }}</f7-nav-center>
            </f7-navbar>
            <f7-block-title>
              Welcome to {{ name }}
            </f7-block-title>
            <f7-block>
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ut quae ad aut minima tempora laboriosam placeat doloribus pariatur ullam dolorem eligendi, quisquam tempore accusamus iure nostrum voluptatum omnis asperiores nemo.
            </f7-block>
          </f7-page>
        </f7-pages>
      </f7-view>
    </f7-views>

  </div>
</template>
