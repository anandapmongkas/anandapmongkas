##### Nama: Ananda Pratama Hadi Pamungkas
##### Kelas: XII RPL 1
##### No: 13

Sesudah melihat modul ke 1,2&3 Kita Memberi MODUL Ke 4
```
https://github.com/anandapmongkas/MODUL-3/blob/main/README.md
```
Langkah Pertama cari folder views seperti di bawah ini:

![image](https://user-images.githubusercontent.com/109930488/183339403-810e381e-df7d-461a-8580-e3282bcf1c0f.png)
# MODUL 4
### Selanjutnya kita akan membuat content yang akan menuju ke halaman barang dan kategori
### Barang :

```
@extends('layout.App')

@section ('title')
    barang
@endsection

@section ('content')
<div class= 'mt-3'>
    <table class="table table-striped">
            <thead>
                <tr>
                    <th width="5%"> No.</th>
                    <th> Nama.</th>
                    <th width="15%"> Kategori.</th>
                    <th width="10%"> Qty.</th>
                    <th width="15%"> Harga Beli .</th>
                    <th width="15%"> Harga Jual .</th>

                </tr>
            </thead>

            <tbody>
                <tr>
                    <td>1</td>
                    <td>Meja</td>
                    <td>ATK</td>
                    <td>1</td>
                    <td>50000</td>
                    <td>55000</td>
                    <td>Hapus | Edit</td>
                </tr>
            </tbody>
        </table>
</div>
@endsection
```
![image](https://user-images.githubusercontent.com/109930488/183339822-f03f24fc-2413-4d26-9351-a4d104cad483.png)


### Kategori :
```
@extends('layout.App')

@section ('title')
    Kategori
@endsection

@section ('content')
<div class= 'mt-3'>
    <table class="table table-striped">
            <thead>
                <tr>
                    <th width="5%"> No.</th>
                    <th> Nama.</th>
                    <th width="15%"> Aksi.</th>
                    
                </tr>
            </thead>

            <tbody>
                <tr>
                    <td>1</td>
                    <td>ATK</td>
                    <td>Hapus | Edit </td>
                </tr>
            </tbody>
        </table>
</div>
@endsection
```
![image](https://user-images.githubusercontent.com/109930488/183339875-2cd3663d-2362-4c88-8f62-65d483ae103f.png)

#### Search dicrome/google
```
http://127.0.0.1:8000
```

![image](https://user-images.githubusercontent.com/109930488/183340256-e7c27392-c538-4cd0-838e-0c73670e618d.png)

![image](https://user-images.githubusercontent.com/109930488/183340339-acdb902a-5caa-4674-9c60-d16455db4e5c.png)

#### SELESAILAH MODUL 4 TERSEBUT
