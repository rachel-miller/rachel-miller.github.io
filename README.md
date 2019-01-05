## ReadME
Personal Site using AirSpace jekyll theme.

## Customisations
### `index.html`
    - General content change(s)
### `airspace.css`
    - Added - `text-align: center`
    - Container is offset so not properly centered
        ```css
        #slider .block h1 {
        font-family: 'Roboto', sans-serif;
        font-weight: 100;
        font-size: 45px;
        text-align: center;
        line-height: 60px;
        letter-spacing: 10px;
        padding-bottom: 45px;
        }
        ```
    - added CSS section to unset container offset in `bootstrap.min.css`
        ```css
        #slider .col-md-10 {
            width: unset
        }
        ```