# Practica4Molina.github.io
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Sitio Educativo - Nivel Medio Superior</title>
    <style>
        /* Estilos básicos */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f5f5f5;
        }
        
        header {
            background-color: #2c3e50;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        
        nav {
            background-color: #34495e;
            padding: 0.5rem;
        }
        
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }
        
        nav ul li {
            margin: 0 15px;
        }
        
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        
        nav ul li a:hover {
            color: #f1c40f;
        }
        
        main {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 20px;
        }
        
        section {
            background-color: white;
            margin-bottom: 20px;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 1rem 0;
            margin-top: 20px;
        }
        
        h1, h2, h3 {
            color: #2c3e50;
        }
        
        .destacado {
            background-color: #eaf2f8;
            border-left: 4px solid #3498db;
            padding: 15px;
            margin: 15px 0;
        }
        
        @media (max-width: 600px) {
            nav ul {
                flex-direction: column;
                align-items: center;
            }
            
            nav ul li {
                margin: 5px 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Mi Sitio Educativo</h1>
        <p>Portal de aprendizaje para nivel medio superior</p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#inicio">Inicio</a></li>
            <li><a href="#matematicas">Matemáticas</a></li>
            <li><a href="#ciencias">Ciencias</a></li>
            <li><a href="#humanidades">Humanidades</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>
    
    <main>
        <section id="inicio">
            <h2>Bienvenidos Estudiantes</h2>
            <p>Este sitio web está diseñado para apoyar tu aprendizaje en el nivel medio superior. Aquí encontrarás recursos educativos, ejercicios prácticos y material de apoyo para tus clases.</p>
            
            <div class="destacado">
                <h3>¿Por qué usar este sitio?</h3>
                <p>Nuestros contenidos están alineados con los programas oficiales de educación media superior y han sido desarrollados por profesores con amplia experiencia docente.</p>
            </div>
            
            <h3>Próximos eventos</h3>
            <ul>
                <li>Taller de matemáticas - 15 de mayo</li>
                <li>Concurso de ciencias - 22 de mayo</li>
                <li>Exposición de proyectos - 30 de mayo</li>
            </ul>
        </section>
        
        <section id="matematicas">
            <h2>Matemáticas</h2>
            <p>Explora nuestros recursos para álgebra, geometría, cálculo y más.</p>
            
            <h3>Álgebra</h3>
            <p>Contenidos sobre ecuaciones, polinomios y funciones.</p>
            
            <h3>Geometría</h3>
            <p>Aprende sobre figuras geométricas, teoremas y demostraciones.</p>
            
            <h3>Trigonometría</h3>
            <p>Funciones trigonométricas, identidades y aplicaciones.</p>
        </section>
        
        <section id="ciencias">
            <h2>Ciencias</h2>
            <p>Recursos para física, química y biología.</p>
            
            <h3>Física</h3>
            <p>Mecánica, termodinámica, electricidad y magnetismo.</p>
            
            <h3>Química</h3>
            <p>Tabla periódica, reacciones químicas, estequiometría.</p>
            
            <h3>Biología</h3>
            <p>Célula, genética, evolución y ecología.</p>
        </section>
        
        <section id="humanidades">
            <h2>Humanidades</h2>
            <p>Material para literatura, historia y filosofía.</p>
            
            <h3>Literatura</h3>
            <p>Análisis de obras, géneros literarios y redacción.</p>
            
            <h3>Historia</h3>
            <p>Historia universal, de México y análisis histórico.</p>
            
            <h3>Filosofía</h3>
            <p>Corrientes filosóficas, lógica y ética.</p>
        </section>
        
        <section id="contacto">
            <h2>Contacto</h2>
            <form>
                <div>
                    <label for="nombre">Nombre:</label>
                    <input type="text" id="nombre" name="nombre" required>
                </div>
                
                <div>
                    <label for="email">Correo electrónico:</label>
                    <input type="email" id="email" name="email" required>
                </div>
                
                <div>
                    <label for="asunto">Asunto:</label>
                    <select id="asunto" name="asunto">
                        <option value="consulta">Consulta</option>
                        <option value="sugerencia">Sugerencia</option>
                        <option value="problema">Reportar problema</option>
                    </select>
                </div>
                
                <div>
                    <label for="mensaje">Mensaje:</label>
                    <textarea id="mensaje" name="mensaje" rows="5" required></textarea>
                </div>
                
                <button type="submit">Enviar mensaje</button>
            </form>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2023 Mi Sitio Educativo - Nivel Medio Superior. Todos los derechos reservados.</p>
        <p>Síguenos en redes sociales: 
            <a href="#" style="color: #f1c40f;">Facebook</a> | 
            <a href="#" style="color: #f1c40f;">Twitter</a> | 
            <a href="#" style="color: #f1c40f;">YouTube</a>
        </p>
    </footer>
</body>
</html>
