<template>
    <div class="countainer-fluid">
        <div class="row">
            <div class="col-lg-12">
                <h2 class="text-center my-4">ISI BUKU KUNJUNGAN</h2>
                <form>
                    <div class="mb-3">
                        <input type="form-control" class="form-control form-control-lg rounded-5" placeholder="NAMA.....">
                        </div>
                        <div class="mb-3">
                            <select class="form-control form control-lg form-select rounded-5">
                                <option value="">KEANGGOTAAN</option>
                            <option value="siswa">siswa</option>
                            <option value="Guru">guru</option>
                            <option value="Staf">staf</option>
                            <option value="umum">umum</option>  
                            </select>
                        </div>
                         <div class="mb-3">
                             <div class="row">
                                 <div class="col-md-4">
                                    <select class="form-control form-control-lg form-select rounded-5 mb-2">
                                    <option value="">TINGKAT</option>
                                    <option value="X">X</option>
                                    <option value="XI">XI</option>
                                    <option value="XII">XII</option>
                                </select>
                            </div>
                            <div class="col-md-4">
                                <select class="form-control form-control-lg form-select rounded-5 mb-2">
                                    <option value="">JURUSAN</option>
                                    <option value="PPLG">PPLG</option>
                                    <option value="TJKT">TJKT</option>
                                    <option value="TSM">TSM</option>
                                    <option value="DKV">DKV</option>
                                    <option value="TOI">TOI</option>
                                </select>
                            </div>
                            <div class="col-md-4">
                                <select class="form-control form-control-lg form-select rounded-5 mb-2">
                                    <option value="">KELAS</option>
                                    <option value="1">1</option>
                                    <option value="2">2</option>
                                    <option value="3">3</option>
                                    <option value="4">4</option>
                                </select>
                            </div>
                        </div>
                    </div>
                    <div class="mb-3">
                        <select class="form-control form-control-lg form-select rounded-5">
                            <option value="">KEPERLUAN</option>
                            <option value="baca">baca</option>
                            <option value="pinjam">pinjam buku</option>
                            <option value="kembalikan">kembalikan buku</option>
                        </select>
                    </div>
                    <nuxt-link to="/pengunjung/">
                        <button type="submit" class="btn btn-dark btn-lg rounded-5 px-5">KIRIM</button>
                    </nuxt-link>
                </form>
            </div>
        </div>
    </div>
</template>