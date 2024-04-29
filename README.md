# Personalización de Formulario con CSS en WordPress

En este README, aprenderás cómo personalizar la pasarela de Izipay con CSS en WordPress para modificar la apariencia
## Paso 1: Elegir el tipo de pasarela de pago

1. En tu panel de administración de WordPress, ve a **Woocomerce**,  selecciona **Ajustes**, clic en **Pagos**, Luego clic en **Izipay pago Standar** y en **Modo de ingreso de datos de pago** encontraras los distintos tipo de pasarelas.    <br>


    #### Formulario Incrustado, Tema Classic
    
    <p align="center">
      <img src="https://i.postimg.cc/P5NpFdhT/Formularios-Izipay.png" alt="Plugin" width="650"/>
    </p>
    <br>

  
    #### Formulario Popin, Tema Classic
    
    <p align="center">
      <img src="https://i.postimg.cc/L4QJ7vBj/popin-classic.png" alt="Plugin" width="650"/>
    </p>
    <br>

    #### Formulario Incrustado, Tema Neon
    
    <p align="center">
      <img src="https://i.postimg.cc/6qMpN6v9/incrustado-Neon.png" alt="Plugin" width="650"/>
    </p>
    <br>

    #### Formulario Popin, Tema Neon
    
    
    <p align="center">
      <img src="https://i.postimg.cc/vZWC1q0n/popin-neon.png" alt="Plugin" width="650"/>
    </p>
    <br>

## Paso 2: Personalizar el formulario

2. En tu panel de administración de WordPress, ve a **Apariencia**, selecciona **Personalizar**.


<p align="center">
  <img src="https://i.postimg.cc/9fgBncDh/perrsonalizar-form.pngg" alt="Plugin" width="650"/>
</p>
<br>

3. En el personalizador, busca la opción de **CSS Adicional**. Esta opción puede estar en diferentes ubicaciones dependiendo del tema que estés usando;
   Luego clic en **CSS Adicional** para abrir el editor de CSS y  puedes agregar estilos personalizados en el editor de CSS Adicional.

<p align="center">
  <img src="https://i.postimg.cc/FshDzC5w/adicional-css.png" alt="Plugin" width="650"/>
</p>
<br>

# Personalizar iconos de tarjetas

1. Actualizar iconos de tarjeta (Visa, Mastercard, American Express y Dinners) en su página.


<p align="center">
  <img src="https://i.postimg.cc/jq1Kwwmr/marca-de-tarjetas.png" alt="iconos de tarjetas" width="650"/>
</p>

<br><br>


- Tener en cuenta que exiten 2 versiones para woocomerce:
  
  WooCommerce Legacy - Shortcode: Estilos que debes usar para una versión de WooCommerce < 8.4 <br><br>

```html
.payment_method_micuentawebstd img:not(.kr-header-logo,.kr-logo-izipay) {
    content: url("https://github.com/izipay-pe/Imagenes/blob/main/logo_tarjetas_aceptadas/logo-tarjetas-aceptadas-351x42.png?raw=true");
    max-width: 200px!important;
```

   Woocommerce Blocks: Estilos que debes usar para una versión de WooCommerce >= 8.4 <br><br>

```html
#radio-control-wc-payment-method-options-micuentawebstd__label img:not(.kr-header-logo,.kr-logo-izipay) {
        content: url("https://github.com/izipay-pe/Imagenes/blob/main/logo_tarjetas_aceptadas/logo-tarjetas-aceptadas-351x42.png?raw=true");
    max-width: 200px!important;
```

<br>


#### Personalización CMS Open Source

| Wordpress - Woocommerce        | Link                                                                      |
|--------------------------------|---------------------------------------------------------------------------|
| Incrustado Clasico             | [Personalization-Woocommerce-Incrustado-Classic](https://github.com/izipay-pe/Personalizacion/blob/main/Personalizaci%C3%B3n%20CMS%20Open%20Source/Wordpress/Tema%20Clasico/Personalization-Woocommerce-Incrustado-Classic.css) |
| Pop-in Clasico                 | [Personalization-Woocommerce-Popin-Classic](https://github.com/izipay-pe/Personalizacion/blob/main/Personalizaci%C3%B3n%20CMS%20Open%20Source/Wordpress/Tema%20Clasico/Personalization-Woocommerce-Popin-Classic.css) |
| Incrustado Neon                | [Personalization-Woocommerce-Incrustado-Neon](https://github.com/izipay-pe/Personalizacion/blob/main/Personalizaci%C3%B3n%20CMS%20Open%20Source/Wordpress/Tema%20Neon/Personalization-Woocommerce-Incrustado-Smartform-Neon.css) |
| Pop-in Neon                    | [Personalization-Woocommerce-Popin-Neon](https://github.com/izipay-pe/Personalizacion/blob/main/Personalizaci%C3%B3n%20CMS%20Open%20Source/Wordpress/Tema%20Neon/Personalization-Woocommerce-Popin-Smartform-Neon.css) |
