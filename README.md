
## ✅ **1. ¿Qué es Laragon Portable y cómo lo usás?**

Laragon Portable es una **suite de desarrollo web preconfigurada** que no requiere instalación, ideal si **no tenés permisos de administrador**.

### 🔧 Pasos para usar Laragon Portable:

1. **Descargar Laragon Portable**:  
   Desde [https://laragon.org/download](https://laragon.org/download)  
   Elegí "Laragon Lite Portable" (.zip).

2. **Descomprimir** en cualquier carpeta donde tengas permisos (por ejemplo `C:\Users\TuUsuario\Laragon`).

3. **Ejecutá `laragon.exe`** (modo portable)  
   No instala nada en el sistema. Se queda corriendo en segundo plano.

4. Desde ahí podés:
   - Levantar un servidor Apache/Nginx local
   - Tener una base de datos MySQL local (opcional)
   - Usar terminal con `composer`, `php`, `npm`, etc.
   - Iniciar Laravel con `php artisan serve`

5. **Agregar tu proyecto Laravel a Laragon:**
   - Copiá tu carpeta del proyecto (`laragraduados`) dentro del directorio `C:\Users\TuUsuario\Laragon\www`
   - En Laragon, clic derecho → “www” → tu proyecto → abrir en navegador  
   - O corré:  
     ```bash
     cd www/laragraduados
     php artisan serve
     ```

6. **Para que Laragon sepa que es un proyecto Laravel:**
   - Agregá `.laravel` en la raíz si querés, o simplemente usá `php artisan serve`.

---

Con eso, tenés un entorno completo, sin instalaciones, sin tocar servicios del sistema operativo.
