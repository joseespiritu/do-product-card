# JLME-Product-Card

Este es un paquete de purebas de despliegue en NPM

### José Luis Espíritu

## Ejemplo

```
import {ProductCard, ProductButtons, ProductImage, ProductTitle} from 'jlme-product-card';
```

```
<ProductCard
    product={product}
    initialValues={{
        count: 4,
        // maxCount: 10
    }}
>
    {
        ({ reset, increaseBy, isMaxCountReached, count, maxCount }) => (
            <>
                <ProductImage />
                <ProductTitle />
                <ProductButtons />
            </>
        )
    }
</ProductCard >
```
