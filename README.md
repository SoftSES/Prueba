# Prueba
Esta es una prueba de versionamiento


package com.softses.entidades;

/**
 *
 * @author usuario
 */
public class CompraDetalle {
    
//codigo
//nombre
//descripcion
//costo unitario
// cantidad
//valor venta
 // iva
    String idfactura;
    String codproducto;
    String cantidad;
    String valor;
    String iva;
    String talla;
    String genero;
    String nombre;

    public CompraDetalle() {
    }

    public CompraDetalle(String idfactura, String codproducto, String cantidad, String valor, String iva) {
        this.idfactura = idfactura;
        this.codproducto = codproducto;
        this.cantidad = cantidad;
        this.valor = valor;
        this.iva = iva;
    }

    public String getIdfactura() {
        return idfactura;
    }

    public void setIdfactura(String idfactura) {
        this.idfactura = idfactura;
    }

    public String getCodproducto() {
        return codproducto;
    }

    public void setCodproducto(String codproducto) {
        this.codproducto = codproducto;
    }

    public String getCantidad() {
        return cantidad;
    }

    public void setCantidad(String cantidad) {
        this.cantidad = cantidad;
    }

    public String getValor() {
        return valor;
    }

    public void setValor(String valor) {
        this.valor = valor;
    }

    public String getIva() {
        return iva;
    }

    public void setIva(String iva) {
        this.iva = iva;
    }

    public String getTalla() {
        return talla;
    }

    public void setTalla(String talla) {
        this.talla = talla;
    }

    public String getGenero() {
        return genero;
    }

    public void setGenero(String genero) {
        this.genero = genero;
    }

    public String getNombre() {
        return nombre;
    }

    public void setNombre(String nombre) {
        this.nombre = nombre;
    }

   
}
