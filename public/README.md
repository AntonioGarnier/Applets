```xml
<?xml version="1.0" encoding="utf-8"?>
<jnlp
  spec="6.0+"
  codebase="https://antoniogarnier.github.io/TiroParabolico/public"
  href="tiro.jnlp">
  <information>
    <title>Tiro Parabolico</title>
    <vendor>Antonio Garnier</vendor>
  </information>
  <resources>
      <!-- Application Resources -->
      <j2se version="1.7+"
            href="http://java.sun.com/products/autodl/j2se"/>
      <jar href="tiroParabolico.jar" main="true" />

  </resources>
  <application-desc
       name="Tiro Parabolico"
       main-class="ControladorTiroParabolico">
   </application-desc>
   <update check="background"/>
</jnlp>
```
