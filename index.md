---
layout: default
---

# Membuat website di github

1. **Registrasi akun github**
2. **Membuat repository**
Klik tombol New


![image](https://user-images.githubusercontent.com/20555943/148685765-6f710d4b-b23e-4297-bb80-23c0154b24c2.png)


3. Isi Repository name. Saya pakai nama: website-github -> pilih public -> klik tombol Create repository.

![image](https://user-images.githubusercontent.com/20555943/148685840-cc798842-1c93-4b3b-80d2-743adcaaab97.png)


4. **Membuat repository di komputer** 
Contoh kita membuat sebuah file index.md
```ruby
mkdir halaman-github
cd halaman-github
echo "Hello World! Welcome to my website" >> index.md
git add index.md
git commit -m "first commit"
```


5. Jalankan script di bawah ini di terminal untuk remote github. Pastikan anda berada di dalam project halaman-github.
```ruby
git init
git remote add origin https://github.com/fauziahkipau/website-github.git
```

![image](https://user-images.githubusercontent.com/20555943/148686728-55b04887-c525-4360-afbb-37725190b0ce.png)


```ruby
git push -u origin main
```



Ketika ingin push git muncul error seperti di bawah ini?
```rubby
remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.
remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.
fatal: Authentication failed for 'https://github.com/fauziahkipau/programmer-otodidak.github.io.git/'
```
**Solusi**, kunjungi link YouTube berikut: https://www.youtube.com/watch?v=iKf8-hhdWjs 

8. Setelah sudah berhasil membuat file index. Buka kembali halaman git, lalu pilih **Settings** -> Scroll ke bawah pilih GitHub Page. Klik link Check it out here!
![image](https://user-images.githubusercontent.com/20555943/148686473-8c937a04-c62e-4e49-88ff-ea2d10e3693a.png)

9. 


<!--
Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```
 
#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
 -->
