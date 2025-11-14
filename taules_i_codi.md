# 3. Taules i codi

> Malgrat en els exemples anteriors o en la pàgina inicial de la pràctica s'han anat utilitzat segons quins elements que surten aquí, aquí s'explica de forma explícita.


# Taules i Blocs de codi en Markdown amb explicacions

## Taules amb alineacions

Per crear una taula en Markdown, utilitza la barra vertical `|` per separar les cel·les i una fila de guions `-` per indicar la capçalera.

Exemple:

| Nom    | Edat | Ciutat       |
| :----- | ---: | :----------: |
| Anna   |   28 | Barcelona    |
| Bernat |   35 | Palma        |
| Carla  |   22 | L’Hospitalet |

### Explicació

- La segona línia amb guions i dos punts defineix l'alineació del text dins la columna:
  - `:---` alinea a l'esquerra.
  - `---:` alinea a la dreta.
  - `:---:` centra el contingut.
- Pots utilitzar format dins les cel·les (negreta, cursiva, enllaços, ratllat).

---

## Blocs de codi amb ressaltat de sintaxi

Per escriure blocs de codi amb ressaltat, utilitza triples backticks ```

Exemples:

```python
def suma(a, b):
    return a + b

print(suma(2, 3))
```

```javascript
function suma(a, b) {
    return a + b;
}

console.log(suma(2, 3));
```

### Explicació

- Els blocs de codi ` ``` ` delimiten el codi.
- El nom del llenguatge (ex: `python`, `javascript`) activa el ressaltat de sintaxi.
- És útil per mostrar codi clar i llegible dins de documentació.

---

```markdown

    # Taules i Blocs de codi en Markdown amb explicacions
    
    ## Taules amb alineacions
    
    Per crear una taula en Markdown, utilitza la barra vertical `|` per separar les cel·les i una fila de guions `-` per indicar la capçalera.
    
    Exemple:
    
    | Nom    | Edat | Ciutat       |
    | :----- | ---: | :----------: |
    | Anna   |   28 | Barcelona    |
    | Bernat |   35 | Palma        |
    | Carla  |   22 | L’Hospitalet |
    
    ### Explicació
    
    - La segona línia amb guions i dos punts defineix l'alineació del text dins la columna:
      - `:---` alinea a l'esquerra.
      - `---:` alinea a la dreta.
      - `:---:` centra el contingut.
    - Pots utilitzar format dins les cel·les (negreta, cursiva, enllaços, ratllat).
    
    ---
    
    ## Blocs de codi amb ressaltat de sintaxi
    
    Per escriure blocs de codi amb ressaltat, utilitza triples backticks ```
    
    Exemples:
    
    ```python
    def suma(a, b):
        return a + b
    
    print(suma(2, 3))
    ```
    
    ```javascript
    function suma(a, b) {
        return a + b;
    }
    
    console.log(suma(2, 3));
    ```
    
    ### Explicació
    
    - Els blocs de codi ` ``` ` delimiten el codi.
      - El nom del llenguatge (ex: `python`, `javascript`) activa el ressaltat de sintaxi.
      - És útil per mostrar codi clar i llegible dins de documentació.
```
---
