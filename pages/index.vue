<template>
  <div class="flex flex-col text-center w-3/4 p-4">
    <Logo class="mb-4" />
    <h1 class="font-semibold text-2xl mb-2">Rona Tembakau</h1>
    <p class="mb-2">
      <b>Segera beroperasi</b>, ide untuk website ini sebenarnya adalah menjadi
      wadah berjualan tembakau, dan info party terdekat, menjual barang legal
      (tembakau, rokok, dsb) yang susah ditemukan di toko e-commerce lainnya
      dikarenakan adanya interverensi <i>sensorship</i> dari negara.
    </p>
    <p class="mb-2">
      Website berikut dikelola secara terbuka, oleh
      <NormalLink url="https://mandaputtra.id" text="Manda Putra" />
      . Kode sumber dapat dilihat di
      <NormalLink
        url="hhttps://github.com/mandaputtra/rona-tembakau"
        text="Github"
      />
    </p>
  </div>
</template>

<script>
import NormalLink from '~/components/NormalLink'

export default {
  components: {
    NormalLink,
  },
}
</script>
