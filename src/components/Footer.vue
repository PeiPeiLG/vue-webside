<template>
  <footer class="bg-primary px-3 pt-4 p-lg-5 fz-7 fz-md-6 border-top border-third">
    <div class="row justify-content-center">
      <div class="col-md-6 col-lg-5 col-xl-4  border-md-right border-secondary">
        <ul class="list-unstyled text-center text-md-left">
          <li><p>Copyright 羅恩培 © 2021 All Rights Reserved.</p></li>
          <li><i class="fas fa-envelope"></i> WebLgEngineer@gmail.com</li>
        </ul>
      </div>
      <div class="col-md-4 pl-4">
        <ul class="list-unstyled">
          <li>           
            <router-link class="nav-link font-weight-bold text-dark text-center text-md-left" to="/about">
             <i class="far fa-address-card"></i> About 關於我
            </router-link>
          </li>
          <li>
            <router-link class="nav-link font-weight-bold text-dark text-center text-md-left" to="/works">
             <i class="fas fa-desktop"></i> Works 作品
            </router-link>
          </li>
          <li>
            <router-link class="nav-link font-weight-bold text-dark text-center text-md-left" to="/blog">
             <i class="fab fa-medium"></i> Blog 部落格
            </router-link>
          </li>
          <li>
            <router-link class="nav-link font-weight-bold text-dark text-center text-md-left" to="/contact">
             <i class="fas fa-edit"></i> Contact 聯絡方式
            </router-link>
          </li>
        </ul>
      </div>
    </div>
  </footer>
</template>