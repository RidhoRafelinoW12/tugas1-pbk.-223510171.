<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Pengenalan Singkat</template>

    Saya biasa dipanggil 
    <a href="https://vuejs.org/" target="_blank" rel="noopener">Ridho atau Rafel</a>
    Suku jawa, anak ke3 dari 3 bersaudara.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Studi Pendidikan</template>

    Saya saat ini berkuliah di Universitas Islam Riau fakultas Teknik prodi Teknik Informatika.
    Saya saat ini sedang menjalani studi Semester 4 dan saya alumni angkatan 2022.
    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Identitas Diri</template>

   Nama Lengkap : Ridho Rafelino Wahyudi<br>
    Tempat/Tgl Lahir : Pekanbaru,05-09-2004<br>
    Gol Darah : B<br>
    Jenis Kelamin : Laki-laki<br>
    Agama : Islam<br>
    Status : Mahasiswa
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Hobi</template>
    !. Membaca Manga/Manhwa dll<br>
    2. Bersepeda<br>
    3. Bermain Game saat senggang<br>
    4. Jalan-jalan Malam Hari<br>
    5. Menonton film

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Sajak</template>
    "Terlambat lulus atau lulus tepat waktu bukanlah sesuatu kejahatan, bukan pula sebuah aib. Alangkah kerdilnya jika mengukur kecerdasan seseorang hanya dari siapa yang paling cepat lulus. Bukankah sebaik-baiknya tugas adalah tugas yang selesai?<br>
    Karena mungkin ada suatu hal dibalik terlambatnya mereka lulus, dan percayalah alasan saya disini merupakan alasan yang sepenuuhnya baik."
  </WelcomeItem>
</template>
