<template>
  <header>
    <b-navbar toggleable="lg" type="dark" variant="dark">
      <b-container>
        <b-navbar-brand to="/">
          <img src="https://kiriminaja.com/assets/home/logo_v1.png" height="50px" alt="">
        </b-navbar-brand>
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <b-nav-item to="about">About</b-nav-item>
            <b-nav-item to="tracking">Tracking</b-nav-item>
            <b-nav-item to="faq">FAQ</b-nav-item>
            <b-nav-item-dropdown right>
              <template #button-content>Services</template>
              <b-dropdown-item to="praktisin">Manajemen Transaksi</b-dropdown-item>
              <b-dropdown-item to="api-integration">Integrasi API</b-dropdown-item>
            </b-nav-item-dropdown>
          </b-navbar-nav>
        </b-collapse>
      </b-container>
    </b-navbar>
  </header>
</template>
