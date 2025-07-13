<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>My Hobby Gallery</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: #f8f9fa;
            color: #333;
            padding: 2rem;
        }

        h1 {
            text-align: center;
            margin-bottom: 1rem;
            color: #0077b6;
        }

        p.intro {
            text-align: center;
            margin-bottom: 2rem;
            font-size: 1.1rem;
            max-width: 700px;
            margin-left: auto;
            margin-right: auto;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
        }

        .hobby {
            background: white;
            padding: 1rem;
            border-radius: 12px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .hobby:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 15px rgba(0,0,0,0.15);
        }

        .hobby img {
            width: 100%;
            height: 180px;
            object-fit: cover;
            border-radius: 8px;
            margin-bottom: 1rem;
        }

        .hobby p {
            font-size: 1rem;
            margin-bottom: 0.5rem;
        }

        .hobby a {
            text-decoration: none;
            color: #ff6f61;
            font-weight: bold;
        }

        .hobby a:hover {
            text-decoration: underline;
        }

        @media (max-width: 600px) {
            .hobby img {
                height: 150px;
            }
        }
    </style>
</head>
<body>
    <h1>My Hobby Gallery</h1>
    <p class="intro">
        Here are some of my favorite hobbies and interests. Each brings me joy and helps me explore new sides of life. 
        Feel free to check out some resources linked below each hobby!
    </p>

    <div class="gallery">
        <div class="hobby">
            <img src="https://images.unsplash.com/photo-1529070538774-1843cb3265df?auto=format&fit=crop&w=800&q=80" alt="Photography">
            <p>I love capturing moments and telling stories through my camera lens. It's a way for me to freeze time.</p>
            <a href="https://www.digitalphotomentor.com" target="_blank">Learn Photography</a>
        </div>
        <div class="hobby">
            <img src="https://images.unsplash.com/photo-1584697964198-f50b4a3f49b4?auto=format&fit=crop&w=800&q=80" alt="Painting">
            <p>Painting allows me to express my creativity and unwind after a long day. Watercolors are my favorite!</p>
            <a href="https://www.youtube.com/results?search_query=watercolor+painting" target="_blank">Watch Painting Videos</a>
        </div>
        <div class="hobby">
            <img src="https://images.unsplash.com/photo-1581404917879-43f98c4c81b3?auto=format&fit=crop&w=800&q=80" alt="Hiking">
            <p>Being in nature recharges me. Hiking up mountains and enjoying scenic views is my weekend therapy.</p>
            <a href="https://www.alltrails.com" target="_blank">Find Hiking Trails</a>
        </div>
        <div class="hobby">
            <img src="https://images.unsplash.com/photo-1526498460520-4c246339dccb?auto=format&fit=crop&w=800&q=80" alt="Cooking">
            <p>Experimenting in the kitchen is so much fun. I love trying out new recipes and cuisines.</p>
            <a href="https://www.bbcgoodfood.com/recipes" target="_blank">Explore Recipes</a>
        </div>
        <div class="hobby">
            <img src="https://images.unsplash.com/photo-1598970434795-0c54fe7c0642?auto=format&fit=crop&w=800&q=80" alt="Gardening">
            <p>Gardening brings me peace. Watching plants grow and bloom feels incredibly satisfying.</p>
            <a href="https://www.gardeningknowhow.com" target="_blank">Gardening Tips</a>
        </div>
        <div class="hobby">
            <img src="https://images.unsplash.com/photo-1607746882042-944635dfe10e?auto=format&fit=crop&w=800&q=80" alt="Coding">
            <p>I enjoy solving problems and building projects with code. It's both challenging and rewarding.</p>
            <a href="https://www.freecodecamp.org" target="_blank">Start Coding</a>
        </div>
    </div>
</body>
</html>
