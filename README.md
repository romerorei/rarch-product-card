# RARCH-Product-Card

Esto es un paquete de pruebas de despliegue en NPM

### Reinaldo Romero

## Ejemplo

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'rarch-product-card';

```

```
  <ProductCard
    product={ product }
    initialValues={{
      count: 4,
      maxCount: 10
    }}
  >

    {
      ( {reset, count, isMaxCountReached, maxCount, increaseBy} ) =>(
        <>
          <ProductImage />
          <ProductTitle />
          <ProductButtons />
        </>
      )
    }
  </ProductCard>

```
