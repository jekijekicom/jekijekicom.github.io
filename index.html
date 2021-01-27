@extends('tempelate')

@section('title', 'Halaman Pegawai')

@section('tabel')  
      @parent          
    <tr>
        <th>Nama</th>
        <th>Jabatan</th>
        <th>Umur</th>
        <th>Alamat</th>
        <th>Opsi</th>
    </tr>
    @foreach($dataKaryawan as $p)
    <tr>
        <td>{{$p->pegawai_nama}}</td>
        <td>{{$p->pegawai_jabatan}}</td>
        <td>{{$p->pegawai_umur}}</td>
        <td>{{$p->pegawai_alamat}}</td>
        <td style="text-align: center;">
            <a class="btn btn-warning btn-sm" href="/editpegawai-{{ $p->id}}">Edit</a>
            <a class="btn btn-danger btn-sm" href="/pegawai/hapus/{{ $p->id}}" onclick="return delete_validation()">Hapus</a>
            <a href="pegawaidetail-{{$p->id}}" class="btn btn-info btn-sm">Detail</a>
        </td>
    </tr>
    @endforeach
    <!--Pengaturan pagination -->
    Halaman: {{ $dataKaryawan->currentpage() }} <br>
    Jumlah Data: {{ $dataKaryawan->total() }}  <br>
    Data per Halama: {{ $dataKaryawan->perpage() }} <br>
    {{ $dataKaryawan->links() }}
@endsection

@section('konten')
    <h3 class="text-center">Data Karyawan</h3>
    <form action="pegawaicari" method="get" class="form-inline">
        <input class="form-control" type="text" name="cari" placeholder="Nama Pegawai" value="{{ old('cari') }}">
        <input class="btn btn-primary ml-3" type="submit" value="Cari">
    </form>
    <br>
    <a class="btn btn-success" href="/pegawai-tambah"> + Tambah Karyawan</a>
    <br>
    <br>
@endsection

<script>
    //validasi  tombol
    function delete_validation() {
        var pilihanuser = confirm('Apakah yakin ingin menghapus data ini?');
        if (pilihanuser) {
            return true;
        } else {
            return false;
        }
        //document.getElementById('pesankonfirmasi').innerHTML = pilihanuser;
    }
</script>
