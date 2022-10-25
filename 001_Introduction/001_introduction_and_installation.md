### Introduction and Installation
-------------------------------------
#### 1. Go Nedir?

Go, cross-platform (Geliştirilen uygulamanın tüm platformlarda Windows,Linux vb. çalışabilmesidir.) ve açık kaynak bir programlama dilidir. 2007 yılında Google tarafından geliştirilmiştir. Go'nun syntaxı(sözdizimi) C++'a benzer. Yüksek performanslı uygulama geliştirmek için kullanılır.

#### 2. Go Ne İçin Kullanılır?

- Web geliştirme
- Ağ tabanlı programlar geliştirmek
- Cross-Platform kurumsal uygulamalar geliştirme
- Cloud-native geliştirme

#### 3. Go Neden Kullanılır?

- Go eğlenceli ve öğrenmesi kolaydır.
- Go'nun hızlı runtime ve compile süresi vardır.
- Go eşzamanlılığı destekler.
- Go'da bellek yönetimi vardır.
- Go, farklı platformlarda (Windows, Mac, Linux, Raspberry Pi vb.) çalışır.

#### 4. Go Installation

Aşağıdaki link üzerinden Go Binary'si indirilmiştir.

https://go.dev/dl/

```
go version  // Go versiyon kontrolü için kullaılan komut.

go version go1.19.2 windows/amd64
```

#### 5. IDE (Integrated Development Environment)

Aşağıdaki link üzerinden Visual Studio Code indirilmiştir.

https://code.visualstudio.com/

#### 6. Hello Go!

Visual Studio Code üzerindeki extension managerdan Go extensionı indirilir. İndirme tamamlandıktan sonra "Ctrl + Shift + p" tuşlarına basarak komut paletini açılır ve "Go: Install/Update Tools" komutu çalıştırılır. Desteklenen tüm araçlar seçilir ve OK tıklanır.

helloworld.go isimli bir dosya oluşturulur ve aşağıdaki kod bloğu kaydedilerek çalıştırılır.

```
package main
import ("fmt")

func main() {
  fmt.Println("Hello World!")
}
```
```
go run .\helloworld.go 
```
Programı çalıştırılabilir bir dosya olarak kaydetmek istiyorsanız, aşağıdaki komutu çalıştırabilirsiniz.

```
go build .\helloworld.go
```