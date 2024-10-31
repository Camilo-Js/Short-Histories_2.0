<script>
    // Puedes agregar aquí la lógica de Svelte si es necesario
</script>

<style>
    * {
        font-family: sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f5f5f5;
    }

    .container {
        display: flex;
        flex-direction: column;
        align-items: center; /* Centra cada tarjeta en la columna */
        min-height: 100vh;
        padding-top: 20px; /* Opcional: Espacio en la parte superior */
    }

    .card {
        background-color: #fff;
        padding: 20px;
        border-radius: 5px;
        box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        margin: 20px;
        display: flex;
        align-items: center;
        gap: 20px;
        width: 80%; /* Opcional: Controla el ancho de cada tarjeta */
        max-width: 600px; /* Opcional: Límite máximo de ancho */
    }

    .image-container {
        width: 200px;
        height: 200px;
        background-color: #ddd;
        border-radius: 5px;
    }

    .card-content {
        display: flex;
        flex-direction: column;
    }

    .card-title {
        font-size: 24px;
        font-weight: bold;
        margin-bottom: 10px;
    }

    .card-description {
        font-size: 16px;
        line-height: 1.5;
        margin-bottom: 20px;
    }

    .button {
        display: inline-block;
        padding: 10px 20px;
        background-color: #007bff;
        color: #fff;
        border: none;
        border-radius: 5px;
        cursor: pointer;
    }
</style>

<div class="container">
    <div class="card">
        <div class="image-container">
            <!-- Aquí va la imagen -->
        </div>
        <div class="card-content">
            <h1 class="card-title">Fast and Easy</h1>
            <p class="card-description">Esta es una breve descripción del contenido de la tarjeta. Aquí se explica de qué se trata el tema.</p>
            <button class="button">Learn More</button>
        </div>
    </div>

    <div class="card">
        <div class="image-container">
            <!-- Aquí va la imagen -->
        </div>
        <div class="card-content">
            <h1 class="card-title">Fast and Easy</h1>
            <p class="card-description">Esta es una breve descripción del contenido de la tarjeta. Aquí se explica de qué se trata el tema.</p>
            <button class="button">Learn More</button>
        </div>
    </div>

    <div class="card">
        <div class="image-container">
            <!-- Aquí va la imagen -->
        </div>
        <div class="card-content">
            <h1 class="card-title">Fast and Easy</h1>
            <p class="card-description">Esta es una breve descripción del contenido de la tarjeta. Aquí se explica de qué se trata el tema.</p>
            <button class="button">Learn More</button>
        </div>
    </div>

    <div class="card">
        <div class="image-container">
            <!-- Aquí va la imagen -->
        </div>
        <div class="card-content">
            <h1 class="card-title">Fast and Easy</h1>
            <p class="card-description">Esta es una breve descripción del contenido de la tarjeta. Aquí se explica de qué se trata el tema.</p>
            <button class="button">Learn More</button>
        </div>
    </div>
</div>
