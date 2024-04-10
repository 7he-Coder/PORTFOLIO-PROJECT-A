# Tecarth

## Google Fonts Link
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;800&display=swap" rel="stylesheet">
or
<style>
  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;800&display=swap');
</style>
* font-family: 'Poppins', sans-serif;

## Fontawesome link
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"
        integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />

### Colors
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  list-style: none;
}

:root {
  --color-primary: #191d2b;
  --color-secondary: #27ae60;
  --color-white: #ffffff;
  --color-black: #000;
  --color-grey0: #f8f8f8;
  --color-grey-1: #dbe1e8;
  --color-grey-2: #b2becd;
  --color-grey-3: #6c7983;
  --color-grey-4: #454e56;
  --color-grey-5: #2a2e35;
  --color-grey-6: #12181b;
  --br-sm-2: 14px;
  --box-shadow-1: 0 3px 15px rgba(0, 0, 0, 0.3);
}

.light-mode {
  --color-primary: #ffffff;
  --color-secondary: #f56692;
  --color-white: #454e56;
  --color-black: #000;
  --color-grey0: #f8f8f8;
  --color-grey-1: #6c7983;
  --color-grey-2: #6c7983;
  --color-grey-3: #6c7983;
  --color-grey-4: #454e56;
  --color-grey-5: #f8f8f8;
  --color-grey-6: #12181b;
}

body {
  background-color: var(--color-primary);
  font-family: "Poppins", sans-serif;
  font-size: 1.1rem;
  color: var(--color-white);
  transition: all 0.4s ease-in-out;
}