# WEB



### Backup SCSS (index.scss)

```scss
$white: #ffffff;
$primary-color: #267668;
$primary-h2: #121212;

* {
    font-family: 'inter', sans-serif;
}

// a,
// a:link,
// a:active,
// a:visited {
//     text-decoration: none;
//     color: currentColor;
// }

.py-150 {
    padding-top: 150px;
    padding-bottom: 150px;
}


.our-services {

    .heading-title {
        font-size: 24px;
        line-height: 1.4;
        font-weight: 500;
        color: $primary-color;
        display: flex;
        justify-content: left;
        align-items: center;
        gap: 8px;
    }

    .icon-btn {
        padding: 12px 24px;
    }

    .primary-btn {
        color: $white;
        background: $primary-color;
        border: 1px solid $primary-color;
        border-radius: 12px;
        position: relative;
        overflow: hidden;
        z-index: 1;
        font-size: 16px;
        line-height: 24px;
        font-weight: 600;
        cursor: pointer;
        transition: all 0.4s ease-out 0s;
    }

    .heading-description {
        font-size: 36px;
        line-height: 1.2;
        font-weight: 700;
        color: $primary-h2;
    }

    .service-list-wrapper {
        // background: url(../../imgs/servies/graphic.png);
        background-repeat: no-repeat;
        background-size: auto;
        background-position: top right;
        padding-top: 32px;
        margin-top: 18px;
    }

    .service-list {
        row-gap: 24px;
        background-color: aqua;

        .card-title {
            svg {
                color: $primary-color;
            }
        }

        a,
        a:link,
        .read-more-btn {
            color: $primary-h2;
            text-decoration: none;
            font-size: 16px;
            line-height: 24px;
            font-weight: 600;
        }
    }



}

@media (min-width: 1440px) {
    .our-services {
        .service-list-wrapper {
            padding-left: 32px;
            padding-right: 32px;
        }
    }
}

```