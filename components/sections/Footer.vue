<script setup lang="ts">
import useSocialLinks from '~/composables/useSocialLinks'

const {
  onClickWhatsapp,
  onClickTelegram
} = useSocialLinks()
</script>

<template>
  <div class="footer">
    <div class="container">
        <div class="footer__info">
        <div>
          <p>Москва, ул. Александры Монаховой, д. 92, к.1</p>
          <p>ИП Иванов Сергей Владимирович</p>
          <p>ОГРНИП: 314547609800635 ИНН: 540290013664</p>
        </div>
        <div>info@top1animator.ru</div>
        <div>
          <a href="tel:+79999999999">+7(999)999-99-99</a>
          <div class="footer__social-links-container">
            <div class="footer__social-links">
              <svg height="30" width="30">
                <use xlink:href="/sprite.svg#telegram" @click="onClickTelegram"/>
              </svg>
              <svg height="30" width="30" @click="onClickWhatsapp">
                <use xlink:href="/sprite.svg#whatsapp" />
              </svg>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>