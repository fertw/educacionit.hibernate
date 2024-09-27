package ar.com.educacionit.clase1;



import java.util.Date;

import ar.com.educacionit.clase1.dao.ProductoDAO;
import ar.com.educacionit.clase1.model.Producto;

public class Main {
    public static void main(String[] args) {
        ProductoDAO productoDAO = new ProductoDAO();
        

        Producto producto = new Producto();
        producto.setNombre("Laptop");
        producto.setPrecio(1200.00);
        producto.setFechaAlta(new Date());

        productoDAO.guardarProducto(producto);

        System.out.println("Producto guardado con éxito");
    }
}
