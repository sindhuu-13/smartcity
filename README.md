
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Design and Analysis of Algorithms</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Poppins', sans-serif;
            color: #fff;
            overflow-y: auto;
            overflow-x: hidden;
            background: linear-gradient(135deg, #007BA7, #005f73);
            height: 100vh;
        }

        .background {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
        }

        header {
            text-align: center;
            padding: 4rem 1rem;
            background: rgba(0, 0, 0, 0.5);
            border-radius: 10px;
            margin: 2rem auto;
            max-width: 800px;
        }

        header h1 {
            font-size: 3.5rem;
            margin: 0;
            background: linear-gradient(90deg, #007BA7, #00A9CE);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        section {
            max-width: 800px;
            margin: 2rem auto;
            padding: 2rem;
            display: flex;
            flex-direction: column;
            gap: 1rem;
        }

        section h2 {
            font-size: 1.8rem;
            color: #00A9CE;
            border-bottom: 2px solid #00A9CE;
            padding-bottom: 0.5rem;
        }

        .box {
            padding: 2rem;
            background: rgba(0, 0, 0, 0.6);
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            text-align: center;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .box:hover {
            background-color: rgba(0, 0, 0, 0.8);
        }

        a {
            color: #00A9CE;
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            text-decoration: underline;
        }

        footer {
            text-align: center;
            padding: 1rem;
            font-size: 1rem;
            background: rgba(0, 0, 0, 0.7);
        }

    </style>
</head>
<body>
    <div class="background"></div>

    <header>
        <h1>Design and Analysis of Algorithms</h1>
    </header>

    <section>
        <h2>Navigate Through</h2>

        <div class="box" onclick="window.location.href='myportfolio.html'">
            <h3>My Portfolio</h3>
        </div>

        <div class="box" onclick="window.location.href='coursereflections.html'"> 
            <h3>Course Reflection</h3>
        </div>

         <div class="box" onclick="window.location.href='teaminfo.html'"> 
            <h3>Team Information</h3>
        </div>

         <div class="box" onclick="window.location.href='teamdis.html'"> 
            <h3>Project Distribution</h3>
        </div>

          <div class="box" onclick="window.location.href='labref.html'"> 
            <h3>Lab Reflections</h3>
        </div>

          <div class="box" onclick="window.location.href='codesnippets.html'"> 
            <h3>Code Snippets</h3>
        </div>
        
    </section>

</body>
</html>
