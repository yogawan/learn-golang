## Referensi
1. Learn Golang and Python Quickly Coding for Beginners with Hands On Projects by J J Tam
2. ChatGPT
3. [Understanding Allocations: The Stack and the Heap - GopherCon SG 2019](https://www.youtube.com/watch?v=ZMZpH4yT7M0)
4. [Belajar Golang Concurrency Gampang](https://www.youtube.com/watch?v=fHxCpoF88Qg)
5. Go for Devpos
6. [Belajar Clean Architecture dari YouTube Backend Magang](https://github.com/medivh13/for_learning_2)

## Hal Penting yang Harus Dipelajari
Goroutine dan sinkronisasi, pointer (constant pointer vs. pointer to a constant), struct pointer, interface, constructor (Go tidak punya, buat manual), pointer function, new pointer, rune, multithread, channel, channel buffer, heap & stack, stack goroutine, garbage collection, escape heap, no escape?, currency = multithreading?, parallelism, goroutines vs. thread?, asynchronous, itoa, atoi
- Goroutine
- Channel, Blocking Channel, Buffered Size Channel
- Range dan Channel Closing
- Select dan Default Selection
- Async Await?
- Deadlock?
- Race Condition
- Time Management: time.Sleep, sync.WaitGroup
- Thread lebih ringan => Goroutine

## Verb
%v: Menampilkan nilai dalam format default. ./  
%T: Menampilkan tipe dari nilai.  
%d: Menampilkan angka desimal (untuk tipe integer).  
%b: Menampilkan angka dalam format biner.  
%c: Menampilkan karakter yang diwakili oleh nilai Unicode.  
%x: Menampilkan angka dalam format heksadesimal (huruf kecil).  
%X: Menampilkan angka dalam format heksadesimal (huruf besar).  
%f: Menampilkan angka desimal (untuk tipe floating point).  
%e: Menampilkan angka dalam notasi ilmiah (huruf kecil).  
%E: Menampilkan angka dalam notasi ilmiah (huruf besar).  
%s: Menampilkan string. tet jooko  
%q: Menampilkan string yang dikutip.  
%p: Menampilkan pointer (alamat memori).  

## New vs Make
![alt text](image.png)

## Go Lang Passing by Value

Ingat, Go secara default menggunakan **passing by value**, artinya perubahan apapun terhadap variabel asli tidak berpengaruh apapun dan hanya dianggap salinan.

<span style="color:red">KECUALI PAKAI POINTER!!!!!</span>

##### * dibaca pointer ke ...
Contoh: `*int` dibaca pointer ke int, `*intPtr` dibaca pointer ke variabel intPtr

##### & dibaca alamat dari
Contoh: `&employee` dibaca alamat dari employee
