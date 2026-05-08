export default function WebsiteProfilDesa() {
  const berita = [
    {
      judul: "Gotong Royong Membersihkan Lingkungan",
      tanggal: "5 Mei 2026",
      isi: "Warga desa bersama perangkat desa melaksanakan kegiatan gotong royong untuk menjaga kebersihan lingkungan."
    },
    {
      judul: "Pelatihan UMKM Desa",
      tanggal: "2 Mei 2026",
      isi: "Pemerintah desa mengadakan pelatihan pemasaran digital untuk pelaku UMKM desa."
    },
    {
      judul: "Pembangunan Jalan Desa",
      tanggal: "28 April 2026",
      isi: "Proyek pembangunan jalan desa tahap kedua telah selesai dilaksanakan."
    }
  ];

  const aparatur = [
    {
      nama: "Budi Santoso",
      jabatan: "Kepala Desa"
    },
    {
      nama: "Siti Rahma",
      jabatan: "Sekretaris Desa"
    },
    {
      nama: "Andi Wijaya",
      jabatan: "Kaur Keuangan"
    },
    {
      nama: "Rina Putri",
      jabatan: "Kasi Pelayanan"
    }
  ];

  const layanan = [
    "Pembuatan Surat Keterangan",
    "Pengajuan KTP & KK",
    "Layanan Bantuan Sosial",
    "Pengurusan Surat Domisili",
    "Pelayanan UMKM Desa",
    "Informasi Kependudukan"
  ];

  return (
    <div className="min-h-screen bg-gray-100 text-gray-800">
      {/* Navbar */}
      <nav className="bg-green-700 text-white shadow-lg sticky top-0 z-50">
        <div className="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
          <h1 className="text-2xl font-bold">Desa Maju Sejahtera</h1>
          <div className="space-x-6 hidden md:flex">
            <a href="#home" className="hover:text-yellow-300">Home</a>
            <a href="#tentang" className="hover:text-yellow-300">Tentang Desa</a>
            <a href="#aparatur" className="hover:text-yellow-300">Aparatur</a>
            <a href="#layanan" className="hover:text-yellow-300">Layanan</a>
            <a href="#berita" className="hover:text-yellow-300">Berita</a>
            <a href="#kontak" className="hover:text-yellow-300">Kontak</a>
          </div>
        </div>
      </nav>

      {/* Hero Section */}
      <section
        id="home"
        className="bg-gradient-to-r from-green-700 to-green-500 text-white py-24 px-6"
      >
        <div className="max-w-6xl mx-auto grid md:grid-cols-2 gap-10 items-center">
          <div>
            <h2 className="text-5xl font-bold leading-tight mb-6">
              Website Profil Desa
            </h2>
            <p className="text-lg mb-6 leading-relaxed">
              Selamat datang di website resmi Desa Maju Sejahtera. Website ini menyediakan informasi desa, pelayanan masyarakat, berita terbaru, dan data penting lainnya.
            </p>
            <button className="bg-yellow-400 text-black px-6 py-3 rounded-2xl font-semibold hover:bg-yellow-300 transition">
              Jelajahi Desa
            </button>
          </div>

          <div>
            <img
              src="https://images.unsplash.com/photo-1506744038136-46273834b3fb"
              alt="Desa"
              className="rounded-3xl shadow-2xl w-full h-[400px] object-cover"
            />
          </div>
        </div>
      </section>

      {/* Statistik */}
      <section className="max-w-6xl mx-auto py-16 px-6 grid md:grid-cols-4 gap-6">
        <div className="bg-white rounded-3xl shadow-lg p-8 text-center">
          <h3 className="text-4xl font-bold text-green-700">3.250</h3>
          <p className="mt-2">Jumlah Penduduk</p>
        </div>

        <div className="bg-white rounded-3xl shadow-lg p-8 text-center">
          <h3 className="text-4xl font-bold text-green-700">1.024</h3>
          <p className="mt-2">Kepala Keluarga</p>
        </div>

        <div className="bg-white rounded-3xl shadow-lg p-8 text-center">
          <h3 className="text-4xl font-bold text-green-700">8</h3>
          <p className="mt-2">Dusun</p>
        </div>

        <div className="bg-white rounded-3xl shadow-lg p-8 text-center">
          <h3 className="text-4xl font-bold text-green-700">12</h3>
          <p className="mt-2">UMKM Aktif</p>
        </div>
      </section>

      {/* Tentang Desa */}
      <section id="tentang" className="bg-white py-20 px-6">
        <div className="max-w-6xl mx-auto grid md:grid-cols-2 gap-12 items-center">
          <div>
            <img
              src="https://images.unsplash.com/photo-1441974231531-c6227db76b6e"
              alt="Tentang Desa"
              className="rounded-3xl shadow-xl"
            />
          </div>

          <div>
            <h2 className="text-4xl font-bold text-green-700 mb-6">
              Tentang Desa
            </h2>
            <p className="text-lg leading-relaxed mb-4">
              Desa Maju Sejahtera merupakan desa yang memiliki potensi besar di bidang pertanian, pariwisata, dan UMKM. Dengan semangat gotong royong, masyarakat desa terus berkembang menuju desa modern dan mandiri.
            </p>
            <p className="text-lg leading-relaxed">
              Website ini dibuat untuk mempermudah masyarakat mendapatkan informasi dan layanan desa secara digital.
            </p>
          </div>
        </div>
      </section>

      {/* Aparatur Desa */}
      <section id="aparatur" className="py-20 px-6 bg-gray-100">
        <div className="max-w-6xl mx-auto">
          <h2 className="text-4xl font-bold text-center text-green-700 mb-14">
            Aparatur Desa
          </h2>

          <div className="grid md:grid-cols-4 gap-8">
            {aparatur.map((item, index) => (
              <div
                key={index}
                className="bg-white rounded-3xl shadow-lg p-6 text-center hover:scale-105 transition"
              >
                <img
                  src="https://cdn-icons-png.flaticon.com/512/3135/3135715.png"
                  alt="Aparatur"
                  className="w-28 h-28 mx-auto mb-4"
                />
                <h3 className="text-xl font-bold">{item.nama}</h3>
                <p className="text-gray-500 mt-2">{item.jabatan}</p>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* Layanan */}
      <section id="layanan" className="bg-white py-20 px-6">
        <div className="max-w-6xl mx-auto">
          <h2 className="text-4xl font-bold text-center text-green-700 mb-14">
            Layanan Desa
          </h2>

          <div className="grid md:grid-cols-3 gap-8">
            {layanan.map((layananItem, index) => (
              <div
                key={index}
                className="bg-green-50 border border-green-200 rounded-3xl p-8 shadow-md hover:shadow-xl transition"
              >
                <h3 className="text-2xl font-semibold mb-3 text-green-700">
                  {layananItem}
                </h3>
                <p>
                  Pelayanan cepat, mudah, dan transparan untuk masyarakat desa.
                </p>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* Berita */}
      <section id="berita" className="py-20 px-6 bg-gray-100">
        <div className="max-w-6xl mx-auto">
          <h2 className="text-4xl font-bold text-center text-green-700 mb-14">
            Berita Desa
          </h2>

          <div className="grid md:grid-cols-3 gap-8">
            {berita.map((item, index) => (
              <div
                key={index}
                className="bg-white rounded-3xl overflow-hidden shadow-lg hover:shadow-2xl transition"
              >
                <img
                  src="https://images.unsplash.com/photo-1494526585095-c41746248156"
                  alt="Berita"
                  className="h-52 w-full object-cover"
                />

                <div className="p-6">
                  <p className="text-sm text-gray-500 mb-2">{item.tanggal}</p>
                  <h3 className="text-2xl font-bold mb-3">{item.judul}</h3>
                  <p className="text-gray-600">{item.isi}</p>
                </div>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* Galeri */}
      <section className="bg-white py-20 px-6">
        <div className="max-w-6xl mx-auto">
          <h2 className="text-4xl font-bold text-center text-green-700 mb-14">
            Galeri Desa
          </h2>

          <div className="grid md:grid-cols-3 gap-6">
            <img
              src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee"
              className="rounded-3xl h-72 w-full object-cover shadow-lg"
            />
            <img
              src="https://images.unsplash.com/photo-1469474968028-56623f02e42e"
              className="rounded-3xl h-72 w-full object-cover shadow-lg"
            />
            <img
              src="https://images.unsplash.com/photo-1470770903676-69b98201ea1c"
              className="rounded-3xl h-72 w-full object-cover shadow-lg"
            />
          </div>
        </div>
      </section>

      {/* Kontak */}
      <section id="kontak" className="bg-green-700 text-white py-20 px-6">
        <div className="max-w-5xl mx-auto text-center">
          <h2 className="text-4xl font-bold mb-8">Kontak Desa</h2>

          <div className="grid md:grid-cols-3 gap-8 text-lg">
            <div className="bg-green-600 rounded-3xl p-8 shadow-lg">
              <h3 className="font-bold text-2xl mb-3">Alamat</h3>
              <p>Jl. Raya Desa No. 10, Indonesia</p>
            </div>

            <div className="bg-green-600 rounded-3xl p-8 shadow-lg">
              <h3 className="font-bold text-2xl mb-3">Email</h3>
              <p>desamajusejahtera@gmail.com</p>
            </div>

            <div className="bg-green-600 rounded-3xl p-8 shadow-lg">
              <h3 className="font-bold text-2xl mb-3">Telepon</h3>
              <p>0812-3456-7890</p>
            </div>
          </div>
        </div>
      </section>

      {/* Footer */}
      <footer className="bg-black text-white py-6 text-center">
        <p>
          © 2026 Website Profil Desa Maju Sejahtera. All Rights Reserved.
        </p>
      </footer>
    </div>
  );
}
