<script setup>
import WelcomeItem from "./WelcomeItem.vue";
import DocumentationIcon from "./icons/IconDocumentation.vue";
import ToolingIcon from "./icons/IconTooling.vue";
import EcosystemIcon from "./icons/IconEcosystem.vue";
</script>

<template class="body">
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Biodata</template>

    <ul>
      <p>Nama : Nurul Ikhsan Siahaan Al</p>
      <p>NIM : 11850114516</p>
      <p>Prodi : Teknik Informatika</p>
      <p>Fakultas : Sains dan Tenologi</p>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Hobi</template>

    <ul>
      <p>Hobi saya adalah bermain Badminton.</p>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Riwayat Pendidikan </template>

    <ul>
      <li>
        <h3 class="font">SD</h3>
      </li>
      <p>Sekolah : SDS Bina Siswa</p>
      <p>Alamat : Di Pondok Palm Agung, Kep. Balam Jaya, Kec. Balai Jaya, Kab. Rokan Hilir</p>
    </ul>
    <br />

    <ul>
      <li>
        <h3 class="font">SMP</h3>
      </li>
      <p>Sekolah : Madrasah Tsanawiyah (MTs) Al-Husna</p>
      <p>Alamat : Di Dusun Salak, Kel. Bagan Sinembah, Kec. Bagan Sinembah Raya, Kab. Rokan Hilir</p>
    </ul>
    <br />

    <ul>
      <li>
        <h3 class="font">SMA</h3>
      </li>
      <p>Sekolah : Madrasah Aliyah (MA) Al-Husna</p>
      <p>Alamat : Di Dusun Salak, Kel. Bagan Sinembah, Kec. Bagan Sinembah Raya, Kab. Rokan Hilir</p>
    </ul>
    <br />
  </WelcomeItem>
</template>

<style>
.font {
  font-weight: bold;
  color: #fff;
  margin-left: 13px;
}

p {
  font-size: large;
  margin-left: 25px;
}
</style>
