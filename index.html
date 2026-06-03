<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Shadow Archive | Famous Encounters</title>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg: #010409;
            --card-bg: #050a15;
            --text-main: #e2e8f0;
            --text-dim: #8892b0;
            --accent: #00e5ff;
            --accent-glow: rgba(0, 229, 255, 0.4);
            --purple-light: #80eeff;
        }

        body { 
            background-color: var(--bg); 
            color: var(--text-main); 
            font-family: 'Inter', sans-serif; 
            margin: 0; 
            padding: 40px 20px; 
            overflow-x: hidden; 
        }

        header { text-align: center; margin-bottom: 60px; position: relative; }
        header::after { content: ''; position: absolute; bottom: -20px; left: 50%; transform: translateX(-50%); width: 100px; height: 2px; background: linear-gradient(90deg, transparent, var(--accent), transparent); }
        h1 { font-family: 'Cinzel', serif; font-size: 3.5rem; color: #fff; text-transform: uppercase; letter-spacing: 8px; margin-bottom: 10px; text-shadow: 0 0 20px var(--accent-glow); }

        .archive-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(280px, 1fr)); gap: 40px; max-width: 1400px; margin: 0 auto; padding-bottom: 60px; }
        
        .entity-card { background: var(--card-bg); border-radius: 20px; overflow: hidden; border: 1px solid #101828; cursor: pointer; transition: transform 0.4s cubic-bezier(0.165, 0.84, 0.44, 1), border-color 0.4s ease, box-shadow 0.4s ease; display: flex; flex-direction: column; }
        .entity-card:hover { border-color: var(--accent); transform: translateY(-8px); box-shadow: 0 12px 30px var(--accent-glow); }
        
        .img-container { width: 100%; aspect-ratio: 3 / 4; overflow: hidden; background-color: #000; }
        .img-container img { width: 100%; height: 100%; object-fit: cover; transition: transform 0.6s ease; }
        .entity-card:hover img { transform: scale(1.08); }

        .content { padding: 25px; flex-grow: 1; display: flex; flex-direction: column; }
        .content h2 { font-family: 'Cinzel', serif; font-size: 1.3rem; color: #fff; margin: 0 0 5px 0; letter-spacing: 1px; transition: color 0.3s ease; }
        .content h4 { font-family: 'Inter', sans-serif; font-size: 0.85rem; color: var(--accent); margin: 0 0 12px 0; border-bottom: 1px solid #1a2436; padding-bottom: 12px; font-weight: 400; letter-spacing: 1px; }
        .entity-card:hover .content h2 { color: var(--purple-light); }
        .content p { font-size: 0.9rem; color: var(--text-dim); line-height: 1.6; margin: 0; }

        .mobile-arrow-container { display: none; justify-content: center; align-items: center; padding: 15px; background: linear-gradient(to top, rgba(0, 229, 255, 0.05), transparent); border-top: 1px solid #101828; }
        .mobile-arrow { width: 30px; height: 30px; fill: var(--purple-light); cursor: pointer; transition: transform 0.3s ease; }
        .bounce-down { animation: waveDown 2s infinite ease-in-out; }
        .bounce-up { animation: waveUp 2s infinite ease-in-out; }
        @keyframes waveDown { 0%, 100% { transform: translateY(0); opacity: 0.6; } 50% { transform: translateY(6px); opacity: 1; } }
        @keyframes waveUp { 0%, 100% { transform: translateY(0); opacity: 0.6; } 50% { transform: translateY(-6px); opacity: 1; } }
        .mobile-panel { display: none; background: #02060d; border-top: 1px solid var(--accent); padding: 25px; }

        .desktop-overlay { display: none; position: fixed; top: 0; left: 0; width: 100vw; height: 100vh; background-color: rgba(1, 4, 9, 0.95); z-index: 9999; overflow-y: auto; padding: 60px 20px; box-sizing: border-box; }
        .overlay-content { max-width: 900px; margin: 0 auto; background: #050a15; border: 1px solid #101828; border-radius: 24px; padding: 50px; box-shadow: 0 20px 50px rgba(0,0,0,0.9), 0 0 40px var(--accent-glow); }
        .overlay-title { font-family: 'Cinzel', serif; font-size: 2.5rem; text-align: center; letter-spacing: 4px; color: #fff; margin-bottom: 10px; text-transform: uppercase; }
        .overlay-subtitle { text-align: center; color: var(--accent); font-size: 1.2rem; letter-spacing: 2px; border-bottom: 2px solid var(--accent); padding-bottom: 20px; margin-bottom: 40px; }
        
        .detail-header { font-family: 'Cinzel', serif; font-size: 1.3rem; color: #fff; margin-top: 25px; margin-bottom: 8px; text-transform: uppercase; letter-spacing: 2px; border-left: 3px solid var(--accent); padding-left: 12px; }
        .detail-text { font-size: 0.95rem; color: var(--text-main); line-height: 1.7; margin-bottom: 20px; padding-left: 15px; white-space: pre-line; }

        .glass-exit-btn { position: fixed; top: 30px; left: 30px; width: 60px; height: 60px; border-radius: 50%; background: rgba(0, 229, 255, 0.05); backdrop-filter: blur(12px); border: 1px solid rgba(0, 229, 255, 0.4); color: var(--purple-light); font-size: 1.8rem; display: flex; align-items: center; justify-content: center; cursor: pointer; z-index: 10000; }
        .glass-exit-btn:hover { background: rgba(0, 229, 255, 0.2); border-color: var(--accent); color: #fff; }

        .archive-disclaimer { text-align: center; padding: 50px 20px; margin-top: 40px; border-top: 1px solid rgba(0, 229, 255, 0.2); color: var(--text-dim); }
        .archive-disclaimer h3 { font-family: 'Cinzel', serif; color: var(--accent); letter-spacing: 3px; margin-bottom: 15px; }
        .archive-disclaimer p { max-width: 800px; margin: 0 auto; font-size: 0.9rem; line-height: 1.8; }

        @media (max-width: 768px) { h1 { font-size: 2rem; } .mobile-arrow-container { display: flex; } }
    </style>
</head>
<body>

    <header>
        <h1>The Shadow Archive</h1>
        <p style="color: var(--accent); letter-spacing: 3px; font-weight: 600;">CLASSIFIED ENCOUNTERS</p>
    </header>

    <div class="archive-grid" id="grid"></div>

    <div class="archive-disclaimer">
        <h3>ARCHIVE NOTICE</h3>
        <p>
            The Shadow Archive functions strictly as a repository for historical anomalies and classified testimonies. 
            We make no definitive claims regarding the objective reality of these occurrences. The dossiers presented herein 
            are compiled from a complex blend of historical folklore, surviving personal journals, and circulating digital accounts.
        </p>
    </div>

    <div id="desktopOverlay" class="desktop-overlay">
        <div class="overlay-content" id="overlayContent"></div>
        <div class="glass-exit-btn" onclick="closeArchiveDetail()">✕</div>
    </div>

    <script>
        const entities = [
            { name: "Agatha Christie", subtitle: "Hotels in England, 1930", img: "https://trilliardaire.sirv.com/%D9%86%D8%B8%D8%B1%DB%8C%D9%87%20%D9%87%D8%A7%DB%8C%20%D8%A7%D8%AF%D9%85%20%D9%87%D8%A7%DB%8C%20%D9%85%D8%B4%D9%87%D9%88%D8%B1/Agatha%20Christie.jpg", desc: "She experienced unexplained noises, shifting objects, and an eerie atmosphere...", full: `<div class="detail-header">Entity / Phenomenon</div><div class="detail-text">Unexplained noises and shifting objects.</div><div class="detail-header">The Account</div><div class="detail-text">She experienced unexplained noises, shifting objects, and an eerie atmosphere in several hotel stays. She remained composed by focusing on routine, prayer, and observation, later incorporating psychological tension and mystery elements into her novels.</div>` },
            { name: "Nikola Tesla", subtitle: "New York, 1906", img: "https://trilliardaire.sirv.com/%D9%86%D8%B8%D8%B1%DB%8C%D9%87%20%D9%87%D8%A7%DB%8C%20%D8%A7%D8%AF%D9%85%20%D9%87%D8%A7%DB%8C%20%D9%85%D8%B4%D9%87%D9%88%D8%B1/Nikola%20Tesla.jpg", desc: "Tesla often reported seeing flashes of light and vivid visual phenomena during experiments...", full: `<div class="detail-header">Entity / Phenomenon</div><div class="detail-text">Flashes of light and vivid visual phenomena.</div><div class="detail-header">The Account</div><div class="detail-text">Tesla often reported seeing flashes of light and vivid visual phenomena during experiments. He considered them part of electromagnetic unknowns and carefully documented everything, believing reality contained layers humans had not yet understood.</div>` },
            { name: "Edward Morley", subtitle: "USA, 1890", img: "https://trilliardaire.sirv.com/%D9%86%D8%B8%D8%B1%DB%8C%D9%87%20%D9%87%D8%A7%DB%8C%20%D8%A7%D8%AF%D9%85%20%D9%87%D8%A7%DB%8C%20%D9%85%D8%B4%D9%87%D9%88%D8%B1/Edward%20Mably.jpg", desc: "Reported physical disturbances in controlled environments, including object movement...", full: `<div class="detail-header">Entity / Phenomenon</div><div class="detail-text">Physical disturbances and object movement.</div><div class="detail-header">The Account</div><div class="detail-text">Reported physical disturbances in controlled environments, including object movement without visible cause. He approached it scientifically, using observation, measurement, and documentation rather than emotional reaction.</div>` },
            { name: "William Shakespeare", subtitle: "London, 1600", img: "https://trilliardaire.sirv.com/%D9%86%D8%B8%D8%B1%DB%8C%D9%87%20%D9%87%D8%A7%DB%8C%20%D8%A7%D8%AF%D9%85%20%D9%87%D8%A7%DB%8C%20%D9%85%D8%B4%D9%87%D9%88%D8%B1/William%20Shakespeare.jpg", desc: "Theatres were often filled with strange echoes, footsteps, and ambient sounds at night...", full: `<div class="detail-header">Entity / Phenomenon</div><div class="detail-text">Strange echoes and ambient sounds.</div><div class="detail-header">The Account</div><div class="detail-text">Theatres were often filled with strange echoes, footsteps, and ambient sounds at night. He used these experiences as creative material, turning unexplained sensations into dramatic and supernatural elements in his plays.</div>` },
            { name: "Leonardo da Vinci", subtitle: "Florence, 1500", img: "https://trilliardaire.sirv.com/%D9%86%D8%B8%D8%B1%DB%8C%D9%87%20%D9%87%D8%A7%DB%8C%20%D8%A7%D8%AF%D9%85%20%D9%87%D8%A7%DB%8C%20%D9%85%D8%B4%D9%87%D9%88%D8%B1/Leonardo%20da%20Vinci.jpg", desc: "He recorded unusual visual effects, shadows, and light distortions in his sketches...", full: `<div class="detail-header">Entity / Phenomenon</div><div class="detail-text">Unusual visual effects and light distortions.</div><div class="detail-header">The Account</div><div class="detail-text">He recorded unusual visual effects, shadows, and light distortions in his sketches. He treated them as optical or natural phenomena and studied them through art, anatomy, and physics-based observation.</div>` },
            { name: "Edward Talbot", subtitle: "Scotland, 1875", img: "https://trilliardaire.sirv.com/%D9%86%D8%B8%D8%B1%DB%8C%D9%87%20%D9%87%D8%A7%DB%8C%20%D8%A7%D8%AF%D9%85%20%D9%87%D8%A7%DB%8C%20%D9%85%D8%B4%D9%87%D9%88%D8%B1/Edward%20Talbot.jpg", desc: "Reported sea-related apparitions appearing in fog near coastlines...", full: `<div class="detail-header">Entity / Phenomenon</div><div class="detail-text">Sea-related apparitions.</div><div class="detail-header">The Account</div><div class="detail-text">Reported sea-related apparitions appearing in fog near coastlines. He described emotional calm mixed with curiosity and carefully navigated the environment while documenting maritime anomalies.</div>` },
            { name: "Ernest Hemingway", subtitle: "Cuba, 1935", img: "https://trilliardaire.sirv.com/%D9%86%D8%B8%D8%B1%DB%8C%D9%87%20%D9%87%D8%A7%DB%8C%20%D8%A7%D8%AF%D9%85%20%D9%87%D8%A7%DB%8C%20%D9%85%D8%B4%D9%87%D9%88%D8%B1/Ernest%20Hemingway.jpg", desc: "He experienced intense, symbolic dreams with threatening figures...", full: `<div class="detail-header">Entity / Phenomenon</div><div class="detail-text">Intense, symbolic dreams with threatening figures.</div><div class="detail-header">The Account</div><div class="detail-text">He experienced intense, symbolic dreams with threatening figures. He used physical activity like walking and writing to process fear, turning psychological tension into literary expression.</div>` },
            { name: "Jane Austen", subtitle: "England, 1815", img: "https://trilliardaire.sirv.com/%D9%86%D8%B8%D8%B1%DB%8C%D9%87%20%D9%87%D8%A7%DB%8C%20%D8%A7%D8%AF%D9%85%20%D9%87%D8%A7%DB%8C%20%D9%85%D8%B4%D9%87%D9%88%D8%B1/Jane%20Austen.jpg", desc: "Occasionally described feeling unseen presences in quiet rooms...", full: `<div class="detail-header">Entity / Phenomenon</div><div class="detail-text">Unseen presences in quiet rooms.</div><div class="detail-header">The Account</div><div class="detail-text">Occasionally described feeling unseen presences in quiet rooms. She maintained emotional control through writing, structure, and reflection, transforming subtle psychological tension into literary depth.</div>` },
            { name: "William James", subtitle: "USA, 1900", img: "https://trilliardaire.sirv.com/%D9%86%D8%B8%D8%B1%DB%8C%D9%87%20%D9%87%D8%A7%DB%8C%20%D8%A7%D8%AF%D9%85%20%D9%87%D8%A7%DB%8C%20%D9%85%D8%B4%D9%87%D9%88%D8%B1/William%20James.jpg", desc: "As a psychologist, he studied reports of spiritual experiences systematically...", full: `<div class="detail-header">Entity / Phenomenon</div><div class="detail-text">Reports of spiritual experiences.</div><div class="detail-header">The Account</div><div class="detail-text">As a psychologist, he studied reports of spiritual experiences systematically. He recorded timing, behavior, and subjective perception, treating them as legitimate psychological phenomena for research.</div>` },
            { name: "André Gide", subtitle: "France, 1920", img: "https://trilliardaire.sirv.com/%D9%86%D8%B8%D8%B1%DB%8C%D9%87%20%D9%87%D8%A7%DB%8C%20%D8%A7%D8%AF%D9%85%20%D9%87%D8%A7%DB%8C%20%D9%85%D8%B4%D9%87%D9%88%D8%B1/Andr%C3%A9%20Gide.jpg", desc: "Reported a feeling of invisible presence in forests and isolated places...", full: `<div class="detail-header">Entity / Phenomenon</div><div class="detail-text">Invisible presence in isolated places.</div><div class="detail-header">The Account</div><div class="detail-text">Reported a feeling of invisible presence in forests and isolated places. He focused on inner awareness and calm observation, interpreting it as psychological and existential experience rather than fear-based illusion.</div>` },
            { name: "Isaac Newton", subtitle: "England, 1670", img: "https://trilliardaire.sirv.com/%D9%86%D8%B8%D8%B1%DB%8C%D9%87%20%D9%87%D8%A7%DB%8C%20%D8%A7%D8%AF%D9%85%20%D9%87%D8%A7%DB%8C%20%D9%85%D8%B4%D9%87%D9%88%D8%B1/Isaac%20Newton.jpg", desc: "In stories and later legends, he is said to have experienced unusual movements of objects...", full: `<div class="detail-header">Entity / Phenomenon</div><div class="detail-text">Unusual movements of objects.</div><div class="detail-header">The Account</div><div class="detail-text">In stories and later legends, he is said to have experienced unusual movements of objects during late-night study sessions. He attributed strange events to natural laws not yet discovered.</div>` },
            { name: "Edward Mably", subtitle: "USA, 1895", img: "https://trilliardaire.sirv.com/%D9%86%D8%B8%D8%B1%DB%8C%D9%87%20%D9%87%D8%A7%DB%8C%20%D8%A7%D8%AF%D9%85%20%D9%87%D8%A7%DB%8C%20%D9%85%D8%B4%D9%87%D9%88%D8%B1/Edward%20Mably.jpg", desc: "Reported unexplained footsteps and hallway disturbances in an empty house...", full: `<div class="detail-header">Entity / Phenomenon</div><div class="detail-text">Unexplained footsteps and hallway disturbances.</div><div class="detail-header">The Account</div><div class="detail-text">Reported unexplained footsteps and hallway disturbances in an empty house. He managed fear by increasing light, staying alert, and documenting each occurrence carefully.</div>` },
            { name: "Charles Devereaux", subtitle: "Africa, 1922", img: "https://trilliardaire.sirv.com/%D9%86%D8%B8%D8%B1%DB%8C%D9%87%20%D9%87%D8%A7%DB%8C%20%D8%A7%D8%AF%D9%85%20%D9%87%D8%A7%DB%8C%20%D9%85%D8%B4%D9%87%D9%88%D8%B1/Charles%20Devereaux.jpg", desc: "Described seeing a luminous jinn-like figure in desert regions...", full: `<div class="detail-header">Entity / Phenomenon</div><div class="detail-text">Luminous jinn-like figure.</div><div class="detail-header">The Account</div><div class="detail-text">Described seeing a luminous jinn-like figure in desert regions. He interpreted it cautiously, maintaining respect and distance while recording environmental conditions and emotional effects.</div>` },
            { name: "Robert Louis Stevenson", subtitle: "Scotland, 1885", img: "https://trilliardaire.sirv.com/%D9%86%D8%B8%D8%B1%DB%8C%D9%87%20%D9%87%D8%A7%DB%8C%20%D8%A7%D8%AF%D9%85%20%D9%87%D8%A7%DB%8C%20%D9%85%D8%B4%D9%87%D9%88%D8%B1/Robert%20Louis%20Stevenson.jpg", desc: "He experienced shadow-like movements in his home environment...", full: `<div class="detail-header">Entity / Phenomenon</div><div class="detail-text">Shadow-like movements.</div><div class="detail-header">The Account</div><div class="detail-text">He experienced shadow-like movements in his home environment. He processed these sensations through writing, transforming fear into imagination for his literary works.</div>` },
            { name: "Hans Christian Andersen", subtitle: "Denmark, 1840", img: "https://trilliardaire.sirv.com/%D9%86%D8%B8%D8%B1%DB%8C%D9%87%20%D9%87%D8%A7%DB%8C%20%D8%A7%D8%AF%D9%85%20%D9%87%D8%A7%DB%8C%20%D9%85%D8%B4%D9%87%D9%88%D8%B1/Hans%20Christian%20Andersen.jpg", desc: "He reported dream-like encounters with strange beings...", full: `<div class="detail-header">Entity / Phenomenon</div><div class="detail-text">Dream-like encounters with strange beings.</div><div class="detail-header">The Account</div><div class="detail-text">He reported dream-like encounters with strange beings. He used storytelling as a psychological release, turning inner fears and visions into fairy tales.</div>` },
            { name: "Louis Pasteur", subtitle: "France, 1860", img: "https://trilliardaire.sirv.com/%D9%86%D8%B8%D8%B1%DB%8C%D9%87%20%D9%87%D8%A7%DB%8C%20%D8%A7%D8%AF%D9%85%20%D9%87%D8%A7%DB%8C%20%D9%85%D8%B4%D9%87%D9%88%D8%B1/Louis%20Pasteur%20(alleged).jpg", desc: "Reported unusual observations in laboratory environments, though interpreted scientifically...", full: `<div class="detail-header">Entity / Phenomenon</div><div class="detail-text">Unusual observations in laboratory environments.</div><div class="detail-header">The Account</div><div class="detail-text">Reported unusual observations in laboratory environments, though interpreted scientifically. He documented anomalies carefully and focused on biological explanations rather than supernatural ones.</div>` },
            { name: "Edward Blore", subtitle: "USA, 1900", img: "https://trilliardaire.sirv.com/%D9%86%D8%B8%D8%B1%DB%8C%D9%87%20%D9%87%D8%A7%DB%8C%20%D8%A7%D8%AF%D9%85%20%D9%87%D8%A7%DB%8C%20%D9%85%D8%B4%D9%87%D9%88%D8%B1/Edward%20Blore.jpg", desc: "Described encounters with red shadow-like entities at night...", full: `<div class="detail-header">Entity / Phenomenon</div><div class="detail-text">Red shadow-like entities.</div><div class="detail-header">The Account</div><div class="detail-text">Described encounters with red shadow-like entities at night. He reduced fear using light sources and structured observation of surroundings.</div>` },
            { name: "Charles Landell", subtitle: "England, 1910", img: "https://trilliardaire.sirv.com/%D9%86%D8%B8%D8%B1%DB%8C%D9%87%20%D9%87%D8%A7%DB%8C%20%D8%A7%D8%AF%D9%85%20%D9%87%D8%A7%DB%8C%20%D9%85%D8%B4%D9%87%D9%88%D8%B1/Charles%20Landell%20.jpg", desc: "Reported moving shadows and unexplained sensations...", full: `<div class="detail-header">Entity / Phenomenon</div><div class="detail-text">Moving shadows and unexplained sensations.</div><div class="detail-header">The Account</div><div class="detail-text">Reported moving shadows and unexplained sensations. He maintained calm analysis and recorded environmental changes systematically.</div>` },
            { name: "Herman Melville", subtitle: "Atlantic Ocean, 1850", img: "https://trilliardaire.sirv.com/%D9%86%D8%B8%D8%B1%DB%8C%D9%87%20%D9%87%D8%A7%DB%8C%20%D8%A7%D8%AF%D9%85%20%D9%87%D8%A7%DB%8C%20%D9%85%D8%B4%D9%87%D9%88%D8%B1/Herman%20Melville.jpg", desc: "Experienced mysterious sea phenomena during long voyages...", full: `<div class="detail-header">Entity / Phenomenon</div><div class="detail-text">Mysterious sea phenomena.</div><div class="detail-header">The Account</div><div class="detail-text">Experienced mysterious sea phenomena during long voyages. He transformed these observations into symbolic literature such as “Moby-Dick,” blending reality and imagination.</div>` },
            { name: "George Washington", subtitle: "Virginia, 1775", img: "https://trilliardaire.sirv.com/%D9%86%D8%B8%D8%B1%DB%8C%D9%87%20%D9%87%D8%A7%DB%8C%20%D8%A7%D8%AF%D9%85%20%D9%87%D8%A7%DB%8C%20%D9%85%D8%B4%D9%87%D9%88%D8%B1/George%20Washington.jpg", desc: "Historical legends describe spiritual visions and unexplained auditory experiences...", full: `<div class="detail-header">Entity / Phenomenon</div><div class="detail-text">Spiritual visions and unexplained auditory experiences.</div><div class="detail-header">The Account</div><div class="detail-text">Historical legends describe spiritual visions and unexplained auditory experiences. He interpreted them through faith, discipline, and reflection.</div>` },
            { name: "Edward Simon", subtitle: "Amazon, 1930", img: "https://trilliardaire.sirv.com/%D9%86%D8%B8%D8%B1%DB%8C%D9%87%20%D9%87%D8%A7%DB%8C%20%D8%A7%D8%AF%D9%85%20%D9%87%D8%A7%DB%8C%20%D9%85%D8%B4%D9%87%D9%88%D8%B1/Edward%20Simon%20.jpg", desc: "Reported luminous forest entities during exploration...", full: `<div class="detail-header">Entity / Phenomenon</div><div class="detail-text">Luminous forest entities.</div><div class="detail-header">The Account</div><div class="detail-text">Reported luminous forest entities during exploration. He observed cautiously and documented without direct interaction, prioritizing survival.</div>` },
            { name: "Thomas Edison", subtitle: "New York, 1890", img: "https://trilliardaire.sirv.com/%D9%86%D8%B8%D8%B1%DB%8C%D9%87%20%D9%87%D8%A7%DB%8C%20%D8%A7%D8%AF%D9%85%20%D9%87%D8%A7%DB%8C%20%D9%85%D8%B4%D9%87%D9%88%D8%B1/Thomas%20Edison.jpg", desc: "He speculated about communication with unseen dimensions and documented unusual sensory impressions...", full: `<div class="detail-header">Entity / Phenomenon</div><div class="detail-text">Unusual sensory impressions and unseen dimensions.</div><div class="detail-header">The Account</div><div class="detail-text">He speculated about communication with unseen dimensions and documented unusual sensory impressions during late work sessions. He approached all phenomena as potential scientific discovery.</div>` },
            { name: "Anthony Weiner", subtitle: "Apartment, 2005", img: "https://trilliardaire.sirv.com/%D9%86%D8%B8%D8%B1%DB%8C%D9%87%20%D9%87%D8%A7%DB%8C%20%D8%A7%D8%AF%D9%85%20%D9%87%D8%A7%DB%8C%20%D9%85%D8%B4%D9%87%D9%88%D8%B1/Anthony%20Weiner.jpg", desc: "Reported fear-related experiences in isolated environments...", full: `<div class="detail-header">Entity / Phenomenon</div><div class="detail-text">Fear-related experiences in isolation.</div><div class="detail-header">The Account</div><div class="detail-text">Reported fear-related experiences in isolated environments. He reduced anxiety by increasing lighting, seeking support, and focusing on rational interpretation.</div>` }
        ];

function renderGrid() {
    const grid = document.getElementById('grid');
    entities.forEach((entity, index) => {
        const card = document.createElement('div');
        card.className = 'entity-card';
        card.innerHTML = `
            <div class="img-container"><img src="${entity.img}" alt="${entity.name}"></div>
            <div class="content">
                <h2>${entity.name}</h2>
                <h4>${entity.subtitle}</h4>
                <p>${entity.desc}</p>
            </div>
            <div class="mobile-arrow-container">
                <svg class="mobile-arrow bounce-down" viewBox="0 0 24 24"><path d="M7.41,8.59L12,13.17L16.59,8.59L18,10L12,16L6,10L7.41,8.59Z"/></svg>
            </div>
            <div class="mobile-panel">
                <h2 style="font-family:'Cinzel', serif; color:#fff; text-align:center; border-bottom:1px solid var(--accent); padding-bottom:10px;">${entity.name}</h2>
                <h4 style="text-align:center; color:var(--purple-light); letter-spacing:1px;">${entity.subtitle}</h4>
                ${entity.full}
            </div>
        `;
        
        card.addEventListener('click', function(e) {
            if (window.innerWidth > 768) {
                // دسکتاپ
                openArchiveDetail(entity);
            } else {
                // موبایل
                const panel = this.querySelector('.mobile-panel');
                const arrow = this.querySelector('.mobile-arrow');

                if (panel.style.display === 'block') {
                    // بستن پنل
                    panel.style.display = 'none';
                    arrow.setAttribute('class', 'mobile-arrow bounce-down');
                    arrow.innerHTML = `<path d="M7.41,8.59L12,13.17L16.59,8.59L18,10L12,16L6,10L7.41,8.59Z"/>`;
                } else {
                    // باز کردن پنل
                    panel.style.display = 'block';
                    arrow.setAttribute('class', 'mobile-arrow bounce-up');
                    arrow.innerHTML = `<path d="M7.41,15.41L12,10.83L16.59,15.41L18,14L12,8L6,14L7.41,15.41Z"/>`;
                }
            }
        });
        grid.appendChild(card);
    });
}

        function openArchiveDetail(entity) {
            const overlay = document.getElementById('desktopOverlay');
            document.getElementById('overlayContent').innerHTML = `
                <div class="overlay-title">${entity.name}</div>
                <div class="overlay-subtitle">${entity.subtitle}</div>
                ${entity.full}
            `;
            overlay.style.display = 'block';
            document.body.style.overflow = 'hidden'; 
        }

        function closeArchiveDetail() {
            document.getElementById('desktopOverlay').style.display = 'none';
            document.body.style.overflow = 'auto'; 
        }

        document.addEventListener('DOMContentLoaded', renderGrid);
    </script>
</body>
</html>
