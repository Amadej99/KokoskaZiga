# Kokoska

#### Seznam placeholderjev regij:

- Jugovzhodna
- Posavska
- Pomurska
- Podravska
- Koroska
- Savinjska
- Osrednjeslovenska
- Zasavska
- Obalnokraska
- Primorskonotranjska
- Goriska
- Gorenjska

Regijam dodamo stran balončka, katerega besedilo želimo nadomestiti (Left ali Right) npr PrimorskonotranjskaRight

#### Seznam CSS razredov

- .container

  - upravlja glavni container (background color, postavitev)

  - ```css
    .container {
      width: 100%;
      height: 100%;
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: gray;
    }
    ```

- svg

  - upravlja z velikostjo same Kokosi
  - ```css
    svg {
      width: 990.7px;
      height: 661.6px;
    }
    ```

- .regija_area

  - upravlja z barvo vseh regij
  - ```css
    .regija_area {
      fill: white;
    }
    ```

- .regija_ime

  - upravlja s predstavitvijo imen regij (barva, font, ...)
  - ```css
    .regija_name {
      fill: #5c5c5c;
      font-weight: bold;
    }
    ```

- .regija_number_left_container

  - upravlja z levim balonckom
  - ```css
    .regija_number_left_container {
      fill: #56762d;
    }
    ```

- .regija_number_right_container

  - upravlja z desnim balonckom
  - ```css
    .regija_number_right_container {
      fill: #5c5c5c;
    }
    ```

- .regija_number_left

  - upravlja s predstavitvijo stevila v levem baloncku
  - ```css
    .regija_stevilo_left {
      font-weight: bold;
      fill: cyan;
    }
    ```

- .regija_number_right
  - upravlja s predstavitvijo stevila v desnem baloncku
  - ```css
    .regija_stevilo_right {
      font-weight: bold;
      fill: cyan;
    }
    ```
