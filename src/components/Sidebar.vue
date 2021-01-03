<template>
  <b-sidebar 
    id="sidebar-backdrop" 
    shadow 
    backdrop-variant="dark"
    backdrop
    bg-variant="dark" 
    text-variant="light"
  >
    <div class="p-3">
          <div class="d-flex align-items-center flex-column">
            <b-avatar variant="primary" text="PS" class="mb-3 mt-3" size="5rem"></b-avatar>
            <h4 id="sidebar-no-header-title">Programando Soluções</h4>
            <div class="divider-menu"></div>
          </div>
        
          <nav class="mb-3">
            <b-nav vertical>
              <b-nav-item active @click="hide"><i class="fas fa-tachometer-alt"></i> Dashboard</b-nav-item>
              <b-nav-item href="#link-1" @click="hide"><i class="fab fa-product-hunt"></i> Produtos</b-nav-item>
              <b-nav-item href="#link-2" @click="hide"><i class="fas fa-user"></i> Usuários</b-nav-item>
            </b-nav>
          </nav>
        </div>
  </b-sidebar>
</template>

<script>
export default {
  name: 'Sidebar',
}
</script>

<style>
.nav-item > .nav-link{
  color: #FFF
}

.nav-item > .nav-link:hover{
  color: #CCC
}

.divider-menu {
  border: 1px solid #FFF;
  width: 100%;
}
</style>
