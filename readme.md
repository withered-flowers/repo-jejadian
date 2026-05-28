# Belajar perintah Git

git config --global user.email ""
git config --global user.name ""

## Ini cuman dilakukan satu kali aja

git init

## ---- ini yang biasanya akan dilakukan berkali kali

```sh
# (save) - cara repot
git add readme.md # <--- tapi ini repot...

# (save) - cara gampang
git add .
git commit -m "menambahkan readme.md"

# Kalau misalnya ada salah message commit
git commit -m "message barunya apa" --amend
```

## -- Ini akan kamu pake untuk ngelihatin kalau ada yang berubah atau gak

```sh
git status
```

## -- Ini akan kita pakai untuk lihat udah simpen apa aja sih?

```sh
git log
```
