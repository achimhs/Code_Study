## 22.08.18

## [๐ฆindex1 ์์ฐ ๋ฌธ์ (๊ด์ด ์ข์์)]

### [๋ฌธ์ ์ค๋ช]

1. **`index1.html`์ ์์ฑํ์์ค.**

   ### <์ด๊ธฐํ๋ฉด>

   ![](../img/8_18_6.jpg)

2. **๋ค์ ์ด๋ฏธ์ง๋ฅผ ์ฐธ๊ณ ํ์ฌ `data`๋ฅผ ๊ตฌํํ์์ค.**

   ![](../img/8_18_7.jpg)

3. **์ปดํฌ๋ํธ**

- ์ด๋ฆ: `childcomp`๋ โํ์ค์นผ ํ๊ธฐ๋ฒโ์ผ๋ก ์์ฑํ์ฌ๋ผ.
- ํฌํ๋ฆฟ: `ChildComp`๋ผ๋ ์์ด๋๋ก ์ค์ ํ๊ณ  ํฌํ๋ฆฟ์ ๋ฐ๋ก ๋นผ๋ผ.

  - ํฌํ๋ฆฟ ์์ญ

    ![](../img/8_18_8.jpg)

- props:
  - `country`: ๋ฌธ์์ด, ํ์๊ฐ
  - `msg`: ๋ฌธ์์ด, ํ์๊ฐ
- ๋ฉ์๋: `check()`

  - ๋๋ผ ์ด๋ฆ์ด โ๊ดโโ์ด๋ฉด์ ๋ฉ์์ง๊ฐ โ์ข์์โ๋ผ๋ฉด ์๋ฆผ์ฐฝ์ โ`์ ๋ต`โ์ด๋ผ๊ณ  ๋ฌ๋ค.

    ![](../img/8_18_9.jpg)

  - ์๋๋ผ๋ฉด ์๋ฆผ์ฐฝ์ โ`์คํจ`โ๋ผ๊ณ  ๋ฌ๋ค.

    ![](../img/8_18_10.jpg)

4. country์ msg๋ `5์ ๋ฐฐ์(*5)`๋ก `๋๋ค`์ผ๋ก ๋์ค๊ฒ ํ๋ค.

### [๋ฌธ์  ํฌ์ธํธ]

- vue component๊ฐ ํต์ 

### [์๊ฒ๋ ์ /์ถ๊ฐํ  ์ ]

<hr/>

## [๐ผindex2 ๊ธธ์ฐ ๋ฌธ์ (์ฌ์์ฑ์ด ํด์ฆ)]

### [๋ฌธ์ ์ค๋ช]

1. `index.html`๋ฅผ ์์ฑํ์์ค.
2. ๋ค์๊ณผ ๊ฐ์ ์ฌ์์ฑ์ด ํด์ฆ ํ์ด์ง๋ฅผ ๊ตฌํํ์์ค.

## <์ฐธ๊ณ  ํ๋ฉด - ์ด๊ธฐ ํ๋ฉด>

![](../img/8_18_1.png)

3. ์ด ํ์ด์ง๋ id๊ฐ `app`์ด๋ผ๋ `div`์์ id๊ฐ `ChildComp`๋ผ๋ ์ปดํฌ๋ํธ 5๊ฐ๋ก ๊ตฌ์ฑ๋์ด์๋ค.

![](../img/8_18_2.png)

4. id๊ฐ `app`์ด๋ผ๋ div์ data๋ ๋ค์๊ณผ ๊ฐ๋ค.

![](../img/8_18_3.png)

5. `props`์ ์ด์ฉํ์ฌ `app`์ `data`์ธ `numbers`์ `result`๋ฅผ `childComp`์ ์ ๋ฌํ์์ค.

- `numbers`- type : Stringํ
- `result`- type : Stringํ, require: true

6. `childComp`์์ `numbers`์ `result`๋ฅผ ์ถ๋ ฅํ  ๋ `v-for`๋ฅผ ์ด์ฉํ์ฌ ์ถ๋ ฅํ์์ค.

7. `childComp`์์ `numbers`๋ฅผ ๋ด์ ๋ฒํผ์ ํด๋ฆญํ๋ฉด `select`๋ผ๋ ๋ฉ์๋๋ฅผ ํธ์ถํ์์ค.

- `select` ๋ฉ์๋

  - ํด๋ฆญํ ๋ฒํผ์ `numbers`๊ฐ โcโ๋ผ๋ฉด, **โ์ ๋ต์๋๋ค!โ**๋ผ๋ ์๋ฆผ์ฐฝ์ ์ถ๋ ฅํ์์ค.

  ![](../img/8_18_4.png)

  - ํด๋ฆญํ ๋ฒํผ์ `numbers`๊ฐ โcโ ๊ฐ ์๋๋ผ๋ฉด, **โํ๋ ธ์ต๋๋ค!โ**๋ผ๋ ์๋ฆผ์ฐฝ์ ์ถ๋ ฅํ์์ค.

  ![](../img/8_18_5.png)

### [๋ฌธ์  ํฌ์ธํธ]

- vue component๊ฐ ํต์ 

### [์๊ฒ๋ ์ /์ถ๊ฐํ  ์ ]

- ์ปดํฌ๋ํธ๋ฅผ ์ฐ๋ฉด ๊ทธ ์์์ for๋ฌธ์ 2๊ฐ ๋๋ฆด ์ ์๊ณ  index๋ฅผ ์ด์ฉํ์ฌ ํ๋ฉด ๋๋ค.
