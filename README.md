# Responsive

Responsive bertujuan untuk mengatur tampilah website agar dapat mengikuti besar kecilnya device yang digunakan

cara menggunakannya bisa ditambahkan langsung pada tag HTML

```<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>

</body>
</html>
```
## Bootsrtap

Bootstrap adalah framework open-source khusus front end yang awalnya dibuat oleh Mark Otto dan Jacob Thornton untuk mempermudah dan mempercepat pengembangan web di front end.

Cara Penggunaan :
```
<html lang="en">
<head>
<meta charset="utf-8" />
<meta http-equiv="X-UA-Compatible" content="IE=edge" />
<meta name="viewport" content="width=device-width, initial-scale=1" /> 
<title>Bootstrap 101 Template</title>
<link href="css/bootstrap.min.css" rel="stylesheet" />
</head>
<body>
<h1>Hello, world!</h1>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
<script src="js/bootstrap.min.js"></script>
</body>
</html>
```
# React JS

ReactJS adalah sebuah library javascript untuk membangun Frontend Web Application dengan Component Based System dan menerapkan konsep Virtual DOM, yang secara sederhananya adalah DOM HTML yang diatur oleh Javascript.

React JS memungkinkan kita untuk menggunakan kembali komponen yang telah dikembangkan ke aplikasi lain yang menggunakan fungsi yang sama. Hal ini tentu menghemat waktu dan tenaga, ditambah dengan kepastian bahwa komponen Anda berfungsi dengan mulus dan tanpa cacat.

ekstensi pada React JS adalah jsx, dengan aturan saat pembuatan function harus diawali dengan huruf besar dan hanya memiliku 1 tag utama (parent tag)

<br>

<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAASoAAACpCAMAAACrt4DfAAAA8FBMVEX5+fn39/fOzs7////8/PwAAADy8vL19fXV1dX//fvm5ubs7OzBwcHe3t7i4uLp6em7u7vIyMjQ0NC9vb22trawsLCkpKSqqqqYmJj///yEhIRYWFiioqKOjo4zMzM4ODgAp9N0dHRnZ2cdHR1JSUnr9PcAn88sLCxSUlJ/f3+Kiorv9e/k7+Rubm4ArNU/Pz/C5O+BzOQiIiI2tNkPDw/Z6tmj0KPN482HwYfZ7fNPvN14xuEVFRWS0ubQ6/Km2OmZzJlSr1J7vntCqUK42bhnt2desV7E4MSh1+hlwt9Butu64O2v1q82ozZxunEknyTufiCNAAAU30lEQVR4nO2dB0PbvtPHZd9FVmRJtmyHBMIII2WW0ZSWUaBQ2jL66/P+381zcga0/w4ndYCWfFtMIjw/Pp1OwzLzJyqkRDE/8CYqoCBhvscmKiDPn6AqqAmqwpqgKqwJqsKaoCqsCarCmqAqrAmqwpqgKqwJqsKaoCqsCarCmqAqrAmqwpqgKqwJqsKaoCqsCarCmqAqrAmqwpqgKqwJqsKaoCqs8lD988BHQ4WIbkE/3f/uJ8V+OsO7NZD1P7jff7VGQsWlsB5qxSMTRQKZtTkqiTLWGAlPRIFRGoPUog6VQZYkTNPq47iAh9NIqHBW8FRaTyVZnPkyDYVGzNKQx2DDKTErUtlgVmZM+mKKxUEc+rpmvWwcF/BwGg1VDSC2nsyMjnxmFWQaoVFjRgBPFCoutHWfADJK0kk99SkRlPdX58HRUMXoKaMypQ1PtFGqRlalsOZlSY0pZrnlDT8LrJ8aLSFlqbCh9ZjiZhyX8FAaza0HzPMwZNzzmEceKKQExpG+SQ8D+sI9G3LEiNLoD4xJTsnME+l4zMr77grQHa38o4wprhI/ghKGYzgSgREScVDU0sLPVNgvjPGuuL5XGCOLfniGv9JIqLyf3LTgLiBAxru/8vRhDzCMUGgRhUow33Ku6GIwEYDIlUWpIyPQWEuFtApkqBLCarmOqFROaw+CKkrgLq7qhU70G6z2u3eX/nnK3bya59JFhIPICnFwY0sRWs2TMGOxSbixUkrnSSk580xiVZwm0VworZU8DhtU3PjEya95KdfJw6BSSiLdSB4mgUFDcRXlLE9ZFYVSuMhBo+QWKdwiK8dEqcjzfSaE4rSVBK0oHlNDZ4AfC2MAXwhogE8mpVIqYGK6Dx4Vv6kgo+Iio08KIQ4UBLZmlSc03bwHyoBhg4KljArBRkjBQCYEN4g2Cutax35G4FJQMrHSCLrB0mf1KOW+qfs8ppudRZbFsuFZOexhfyiMre+HtazGY1+ZlO4AmsynEldlMomkELIex8ZkisplEMZXSgvKfgEfuogZzarooNqHWRmDNlAHS2E5KgY1bawnpNEKahGFVbGmG0xrKD2lfAqrQAUKG74X1UMfZFlmlZcVVNQilbnkLl0eDzmjQjDfvwfx4A9uPd4P7oauO4zqq1SQZWROGGRxLUyd45RZWkukYkJaHqu6Tvw4FhkyL1ZTkjInV+ilQFuFWZpFAuxYisP/FZZ0S/4kWOhuFuSxlbuXXv9+5bFUwPo3Mv/NewehChAEZbdC9HfnjhdGwXdokJXD6oHbq6RKTdlhKELWC50yj/yUyORdUwZlPPINMS+jwB0N1ffRsctL34TMP/MHyHnZpMJakoIfB9IYwdBoIPcdpgIlVUxDyvZTARXIIv7zOzR6XNVri3ILrZz71nexsBaJC5fJif/p+f1WlKF1lhhua4pqmyiVTiMeQxxmkPGM6lhkVTaMPfHHRxotWFCZYRoNj2xAQRSfIq9OtQuq6fkZxYExj/SUZany7IOgYkTJtxlHh6o2G4KoKaON1xAhoENFhbKf/rGbGTGugjS0oPhGSAaWgR+6gsYqoFAwrmuWaenzzBPiIVAJlaUiTX2qHVCoJAUoG2SJ4q6sjamYJYM3Qvnx46DqxVV1XqPoCKZ6qMi2UhBxSpGMQ5VCXfgP0EDlAiiKnAIvd6FUPUXOvJCCFCp5eej8JWgNJUQmI8dVXpbWDaGguMrrooqoFlpTStVUIiKtVaYeBNXvpWql7OaP4qruhoN4quvjFcsLucBVxEo5xT9WSQ0bpcdVqMvc21NS+SHok8hz49Ckd7mwxoHqiaAv/bLKR4XJk+gbLT3+HQcq8SRQoS15h/8wqrKNeyyoHqjR7tdCU06L9EDjQKWjcnc4ovjQfTK/1jhQlX07RxSW7NfHESyY0hs6R9LfgErqp4Gq5OJlHKiip4Gq7Fs2DlRhWd1Jfyiv3DagfxkVK9dZjQMVfyKosNwrGweqoOSAZlSVHAuPpWXhabQTl+3Xx9Je9VRQlRuvjwNV2bHfyCr3RCaoCuvfRlVqvP5PoypXY3HrT6Jpr3SNiKparf70b/1R4u4jwGA53P6/2WGB0VEII1ty0bMbDdXp8fHuz1hh6qHpxusolpYChvHSzK/Opt3+wf7vXTiqLA1/BILfRZggGtkQncj8nt17c788u3srDo3KGdThSeu22ret+0sSVEKYXQQyJWSBWeYuvFl1JwP3bl++tvuPbPpmb/r7XZ20pu/vcGamQsFkvj1APmTefYZ4rm9KkK1mMwnmxwSn7hpssA3k22CeTKtMTQ2MELNmVMwgh0bV3jva86qHL8gUDuljO09oVw+Pj056p/2aQ30dosVmSie4SqhQzrtTnWs2+ufk7R1dYfv4sL23e3i8fXTcrt66xe7e1fVh9fD65Pp6mna4199hBOsN4OvNDLCx9FIgRutLU9Borsz0RlRDxRAC9JdeGpjamJuZg7S+tOFhvg1r1JsZQrK0pCGZmlmKWGNtbaYfndL6Y8qA7e3O1TWrXm3TzT+72t3em+5cnxKw1snu4MrmGs0ZWFDRgkZvgAoai9HSbO+sOke3rbPpo+ujDuW11t6Jd9U6O7qZPm6dtPZw+/q6dcW293b3qr0dJmZHwUocrSSYyeQVstXYZGBm13ut+CjfuXsRVrR6BStqIV3hGztyfQ6as3I+gUpdVJhc1voVy5Z1Yx3M3JzuZ16YmhsPqupVi3IGq15f0+L26Gb7ZLrTOUPmtY76zgteT2WLG/J1vd6swz1UOwJsMz+r6u6LvTOCfNjqtOlLq13F7aOr61b16Hh6++y21W6/2PW2b277O1xeebcOulKrL82BXV+soFggE6Jc179I1MsOVfwSYFWu8SZfCjemQCxgBWB2A95xWOH1tXr9tc4WQTcpcXaAZ/ZV0YrisKiOb6bpCqYJUfX2xdkuuaz2yfZRtXq41zrpGwFlwBmzY5WVZFUB9lAtCPB7qE5aVycnu/TLAT/p0NZkWSdX3vZZu3W615l29Np7rYFVRbCq9bKvrBGrWr7DZAfc+KQuKnSLCidHRRxg1fRQ1UHM56hm4JVDNbto3XC+9e9R6aV4TKjIn5/tYvXF8W37qnW496J9etu+vpk+2z3c7l8ZufWpdVw2YCTiTuLSKiEDyg/rXTMgyLe7J+ysdfbilFWPOreHrLV3enbafnG4+4LREToddrt72Dnu79BAtgavNMhQNcGvsKCigTwWGSkB89cCBksbdDRZQVMhKg7VXBNm18HlWwXLhCokcJCwWhdVfXHg1qE+Ll/F9jo3lGtOjm4O20edvesqXdd1m0yjs9fbDTQ5xLOgVxbWCJVYW6KkdGcDvKXVxd4+kFY/ad/cTh+TJZ5e35xWT286R+3dG3Z2NN0+ut7bmz7rdI57QQQs0X6WZLSysGJgcX79pYd6ZX4dmLexUAdMmi5KWFzdIaDzOwmsBzN8js+9XGhyjFbmG8CWOCyGkM4vLDI7C4ZiA29xoT/4eYyo7pXqVbes3n3sKS+Ye8Xy/SD0XrDQ25L19kUruATsJtzbbW+H6H565Xy/4B+EAnkGZP0/0sL9g5na3XrQO6c8huiuD3fBQvK6Pq64qri+r9+gS+gO8ccxV35gtvCQeTQFVx0jKliQ35wDpOSqcM2V0hjtLI63Sj1EPafoMyWloYLujB2D/67MM9i3/XxM7Q53cbWrRiAVVmUc9EFVEipovNx5lfCVlVUNS0srqxwaq83XEubmFxoAcy93VgXotRzPO+d5agXrXU9JpaFyHNbrVPBBswYvFX+NvBKJHYCFCDaWgHGggtqtueyqc3ON54tqjoI6XFlrNglVAhs1F73MR7XVZpPsjIoj52nzUhlWBcJSRf59rX9looI191S3QzVTkwsAr6J43YXVXVSY5v4JXktnVUUrXk9IZaHaoByFaietz8GaD5QTd6YaFclWp+L10H11tdl5F2cRw+ftq1C4SieIuSkDfojCIG+kliOfaljmvjIXdSfOnmrPvAQczEoB2G8whjwJ+pNXuFivTr/n8nkpwp21YQOfR58q7CGfhpjOfVX38+8atDc36af7ES+/7NOJfvmy+YPVSj3BX2vcqJD1q3mMXZ9V+4/goGsqZt3F/ZUHNbM37xH/2+za0tuDN8i8tx/f9qfAGaz/5Q0+3EM9Y0bV3m2fnVa92zOvenjbOtmlhOrhKXq77dtddnp4u3tvvp19tr/1ZQv3N10mfvMe4L9N3PpCfODSEYEDhyq4vHSni7jlOH7YRNpmn750CfJx1izHi6p69qLTufY6pOpJp3V0xPa2p69vpk8p+aa6vd150W9o2XxzfgHnXy//2/x8fvEW4M3B1v5/m1sfLi/eIOao0KHC8zfvPxKWzx8/bVHOPAD4+unyw9b++de3rjK1UrRBZRSNGdXedhtpcXrbOp2+2q5Wq0fH1c7J9FnrsMraL25Pe6g8umAP8XwL3nwB3D84f/vlw8XF/7GLS6LF7lDh/ieA880vH95sYW5UDL5+BiKGW+8/fEaMxzkGZ8yoOntVWpCODqvHrnm4deW1dqvXR9W8Uf2q1b007+DjF8p35wFevgf29uLjfp4B2cevBxfvvXuoPn8F+LR/+fH9PlnY5wsKe7/uu0R8e/DxMxbu/RxJ40WFrTOH6nqanVar28foLOnsRXs6J3i1jcdH/a6Gzcvzj3D+Fg4uP/93sI+Qu3V2cJlHH58P3PLgMxnPByBvj0TzwxZQHiRUl/Dmzf5/F/uuQUONc7TEeFGdtg5dB812i5BRPmwd4nbrpsPa27d5r89052TQ1ImwhZ8+XpzjVj5BiUP1YdM7v/h6QaXf+SfyU/sfvm7BwcdP7/PG1c3Nt19d3H/x6eIDRRZ5+xQ0x1kJGC8qL3dF1fZh2zUEux53+nFLl+w+fnNoPN/cGmzp5UETbm3lEcKmm13tXgJjedbLl1uDncBYa+FloSrDS+Cn7ycJKnDcHFhP3P4FvipsltEA9fvY+39Rbv76zyWqLKvirx9iUBUa/njzRpeWAXce5HGtSPjWFzJ8DGDlodIP0qzi5gQJjbDWirC8GTMLqTRU8XL2YOedMwqJFxkY9x4KWGmoFmcf+jHcnJdxOVJHD5EhS0O18DiPljpEXqh9ypAyGC+w8lA9Zh+My5GhTqxNdDS2DDk0qh+fBp+pPHpjuUPEI2dgifS+cfn4iwJgMNXjb4OyYVHxHxtP8GTm4HFUeM5Lh72ZumUtjo31Bg2wdz/umUGmYstlAuHvGnCGRIWi+fKH5vPYfQTfKuclyeO7KW1RSwBUHiN2XoQaMRBBhCIfWIxKGOACVPTbwdzDWhXCuz+4hIcV9nuKMusTqkzWooaqJ36Yycw0jHLTQaDimZ8EDBq/9bVD+yp4N9aJ5scg1DoIUCXKJhhDDZSySrMMuGvcAsWQhxkI/7dDQodHtfpEpgYoLBSJ1J4iS/I9BRlTQhnhZhSnC5FhHGZGqDAF87tmweFRzVbG9DKMsYkLIXiIUnAWYhhw1CJgPJ9NWPscPW1QktP/3fQsI2TA6NHDgmHVd1p337/5VDAOGx7V8t/mq8rS8CXg678s+5WmYeMq/9VfON6uHA1vVc+V1GRe0OKaoCqsCarCepKocPCCkgJ6sLN/iqjQKD/vY8Dem0QGj1n0Bkv2396V98j7Qfd9FGNvMX6KqLgCRBkLo0XqI2pfKoNCRcJPuXuRVxgbE8hQKOXW8plGHRsh4jE37j9BVN1ppxQoa2kRYCJq0mr3uiyNShsRpRBbTPisFyZurSykuq8SFoo+LjqiRkTVHT08+Np71A9+GnQNFYxJCxjYaMpyxRvuTQo+I2o6sK4hjs+SjdV9rIcKQuvLKStUKHTNvQn0KaJCk9GiNrD45uqKeyprfXX1Jw1ktWG66clXqVD7RqOx2mOSuzfBWBUZFkaeSiItVJBqaVAzQWtBGCbCRBzH3Do0GirIKuRLK37//YgyqTgWkeyN2vnOxWL6aqgWZey/bHHQJNB7uxBDHcZca4HYf+fQnYcfd6P1CKgQeBi/QwaECsLMtYhhlKNCzFEhU9k374uC1Rgk/8nTjHinAgfnIkDzOI2LwzfCgFivpOk78ksVH1Tl5cqae3Km0n11aY4q2Fl5Wbk3iyPadwi1yrroubIBmYCHkTRkJEIkTn53J1p2g4Lea6rwLkAYxA2PoWFRebX55UYIcWV1dbWSeJUEYCfGb1BBfRVgrnnP6a/VgQyv8W6hlo85T/yuEiG0kVHIOXevzusjoBLQsCgVnk4iH7USoFMZGaUhUsbo9LGmKB8SFbyqKAAkVEkiKompbGzMLWzAt6gW5wCTymAbFJXckwCklfn8+Xj8ZaZDnQqIQchZU5e6Ab4h6+UNsFLxWGeQ/uElj6qh+wHXKy8tQPyOeFUSXamRxHdW9ZJQicrdCM2lRv78sl2qrBfxMuhiyxS0UWi5qIHQglBZEEkmuHvd5/BXWYqGb69i9fmKn+ZuPeGVqBtL8UrutbGiCWFjBWBqZfC4DGF046QrC7Vi83GhCbiWMbFhWvJY0YdYU7ggwCoRhd5jzWU7QgkIkIhesACzlcbsjnvl3drKonHPky4vWggr641K2vdVsJg/A58khRsFkQ1ePUiIoefa+6MLHq0je6S4CvshKIJoNLpv9kjr+QQKtq4Rw9mG6HNBU+FDdIs8Yf1JxabnrHvlVi8Q6M1uctd9JGr/SBPz+KvL+I+QeootC09VE1SFNUFVWBNUhTVBVVgTVIU1QVVYE1SFNUFVWBNUhTVBVVgTVIU1QVVYE1SF9YxR3Zt0gN2Nmg5+SuP5oep3W4MP/V5sP1T93kZIzF2Hdf/vvYlrnhsqFDaTmMTazAoTK0xUykRomfVULNFPUylj61bLfBSxD1bZJMu7o54fKmUw0yqsBRlE0poa0/RNZYEKMTMJpLIeWoGRAmMs2VgdlA7yCaGfHyrLQflWu2e3Mmm1Qvc00lTmKQZpIglOTesQjADQGqSIwY9Y+jxRqdRXXiZSsq1UZD1UNogNAaT0eqQSFaYsFlmQiczLnjEqG0VUzkmPeZxFAS08L2ABcuQRsoBSWMTdzPBRgF7kYV46PlNfJfiIPZLPDtXondPPD9XIIlRJ4E1UQEHCVH9o2ES/VKL+H+1Dh8LlzHyyAAAAAElFTkSuQmCC">

Curly Braces merupakan penggunaan/penambahan kurung kurawal pada tag html

contohnya : 
```
<h1>{1+1}</h1>
```
maka hasilnya akan menjadi 2