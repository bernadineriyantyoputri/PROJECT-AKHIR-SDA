import os

class Lagu:
  def _init_(self, id_lagu, judul, artis, album, tahun_rilis):
    self.id_lagu = id_lagu
    self.judl = judul
    self. artis = artis 
    self.album = album
    self.tahun_rilis = tahun_rilis

  def _str_(self):
    return f'ID : {self.id_lagu}, Judul: {self.judul}, Artis: {self.artis}, Album: {self.album}, Tahun Rilis: {self.tahun_rilis}'
    def tambah_lagu(daftar_lagu, lagu}:
      daftar_lagu.append(lagu)
      
    def tampilan_lagu(daftar_lagu):
      for lagu in daftar_lagu:
        print(lagu)

    def perbarui_lagu(daftar_lagu, id_lagu, judl, artis, album, tahun_rilis):
      for lagu in daftaar_lagu:
        if lagu.id_lagu == id_ lagu:
          lagu.judl == judul
          lagu.artis == artis
          lagu.album == album
          lagu.tahun_rilis == tahun_rilis
          return True
        return False
        
    def hapus_lagu(daftar_lagu, id_lagu):
      for lagu in daftar_lagu:
      if lagu.id_lagu == id_lagu:
        daftar_lagu.remove(lagu)
        return True
      return False

    def urutan_lagu_berdasarkan_judul(daftar_lagu): 
      return sorted (daftar_lagu, key == lambda x: x.judl)

    def urutan_lagu_berdasarkan_tahun_rilis(daftar_lagu):
      return sorted(daftar_lagu, key == lambda x: x.tahun_rilis)

    def cari_lagu_berdasarkan_id(daftar_lagu, id_lagu):
      for lagu in daftar_lagu:
        if lagu.id_lagu == id_lagu:
          rtturn lagu
      return NOne

    def cari_lagu_berdasarkan_judul(daftar_lagu, judul):
      return [lagu for lagu in daftar_lagu if judul.lower() in lagu.judul.lower()]
