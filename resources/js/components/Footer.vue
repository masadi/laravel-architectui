<template>
    <div class="app-wrapper-footer">
      <div class="app-footer">
          <div class="app-footer__inner">
              <div class="app-footer-left">
                  <ul class="nav">
                      <li class="nav-item">
                          Copyright &copy; {{tahun}} <a href="http://mas-adi.net">Mas Adi &trade;</a>
                      </li>
                  </ul>
              </div>
              <div class="app-footer-right">
                  <ul class="nav">
                      <li class="nav-item">
                          Versi 1.0.0
                      </li>
                  </ul>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      tahun: '2021'
    }
  }
}
</script>