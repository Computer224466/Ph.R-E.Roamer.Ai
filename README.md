# Ph.R-E.Roamer.Ai
 

https://cloud.google.com/shell/docs/using-web-preview?cloudshell=true#simple_server_example





 // Set up asset cache

registerRoute(

  ({ request }) => ['style', 'script', 'worker'].includes(request.destination),

  new StaleWhileRevalidate({

    cacheName: 'asset-cache',

    plugins: [

      new CacheableResponsePlugin({

        statuses: [0, 200],

      }),

    ],

  }),

);





    <meta name="author" content="PH.R E.ROAMER Advanced Team">

    

    <!-- PWA & Mobile -->

    <meta name="theme-color" content="#5D5CDE">

    <meta name="apple-mobile-web-app-capable" content="yes">

    

    <!-- Advanced Libraries -->

    <script src="https://cdn.tailwindcss.com"></script>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/marked/9.1.2/marked.min.js"></script>

    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">

    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&family=Amiri:wght@400;700&family=Cairo:wght@200..1000&family=JetBrains+Mono:wght@400;700&display=swap" rel="stylesheet">

    

    <!-- Ultimate Tailwind Configuration -->

    <script>

        tailwind.config = {

            darkMode: 'class',

            theme: {

                extend: {

                    colors: {

                        primary: '#5D5CDE',

                        'quantum-blue': '#0066FF',

                        'neural-purple': '#8B5CF6',

                        'consciousness-cyan': '#06B6D4',

                        'wisdom-gold': '#F59E0B',

                        'earth-brown': '#8B6F47',

                        'sage-green': '#7A9B7F',

                        'cosmic-dark': '#0F0F23',

                        'quantum-light': '#F0F9FF',

                        'hybrid-pink': '#EC4899',

                        'fusion-orange': '#F97316'

                    },

                    fontFamily: {

                        'arabic': ['Amiri', 'Cairo', 'sans-serif'],

                        'inter': ['Inter', 'sans-serif'],

                        'mono': ['JetBrains Mono', 'monospace']

                    },

                    animation: {

                        'quantum-pulse': 'quantumPulse 4s ease-in-out infinite',

                        'neural-flow': 'neuralFlow 8s linear infinite',

                        'consciousness-wave': 'consciousnessWave 6s ease-in-out infinite',

                        'holographic-shift': 'holographicShift 10s ease-in-out infinite',

                        'hybrid-rotate': 'hybridRotate 12s linear infinite',

                        'data-stream': 'dataStream 3s linear infinite'

                    }

                }

            }

        }

    </script>

    

    <!-- Ultimate Quantum-Hybrid CSS -->

    <style>

        /* Advanced Design System */

        :root {

            --quantum-primary: #5D5CDE;

            --quantum-secondary: #8B5CF6;

            --neural-glow: rgba(93, 92, 222, 0.3);

            --consciousness-flow: linear-gradient(45deg, #5D5CDE, #8B5CF6, #06B6D4, #F59E0B);

            --quantum-glass: rgba(255, 255, 255, 0.1);

            --hybrid-gradient: linear-gradient(135deg, #5D5CDE, #8B5CF6, #EC4899, #F97316);

        }



        body {

            font-family: 'Cairo', 'Inter', sans-serif;

            background: linear-gradient(135deg, #0F0F23 0%, #1a1a3a 25%, #2d2d5f 50%, #1a1a3a 75%, #0F0F23 100%);

            background-size: 400% 400%;

            animation: holographicShift 20s ease-in-out infinite;

            overflow-x: hidden;

        }



        /* Ultimate Animations */

        @keyframes quantumPulse {

            0%, 100% { 

                transform: scale(1) rotate(0deg);

                filter: hue-rotate(0deg) brightness(1);

                box-shadow: 0 0 20px rgba(93, 92, 222, 0.3);

            }

            25% { 

                transform: scale(1.05) rotate(90deg);

                filter: hue-rotate(90deg) brightness(1.2);

                box-shadow: 0 0 30px rgba(139, 92, 246, 0.4);

            }

            50% { 

                transform: scale(1.1) rotate(180deg);

                filter: hue-rotate(180deg) brightness(1.4);

                box-shadow: 0 0 40px rgba(6, 182, 212, 0.5);

            }

            75% { 

                transform: scale(1.05) rotate(270deg);

                filter: hue-rotate(270deg) brightness(1.2);

                box-shadow: 0 0 30px rgba(245, 158, 11, 0.4);

            }

        }



        @keyframes neuralFlow {

            0% { 

                background-position: 0% 50%;

                transform: translateX(0) scale(1);

            }

            50% { 

                background-position: 100% 50%;

                transform: translateX(10px) scale(1.05);

            }

            100% { 

                background-position: 0% 50%;

                transform: translateX(0) scale(1);

            }

        }



        @keyframes consciousnessWave {

            0%, 100% { 

                transform: translateY(0) scale(1) rotate(0deg);

                opacity: 0.8;

            }

            33% { 

                transform: translateY(-15px) scale(1.05) rotate(120deg);

                opacity: 1;

            }

            66% { 

                transform: translateY(-10px) scale(1.1) rotate(240deg);

                opacity: 0.9;

            }

        }



        @keyframes holographicShift {

            0%, 100% { 

                background-position: 0% 50%;

            }

            25% { 

                background-position: 25% 75%;

            }

            50% { 

                background-position: 100% 50%;

            }

            75% { 

                background-position: 75% 25%;

            }

        }



        @keyframes hybridRotate {

            from { transform: rotate(0deg); }

            to { transform: rotate(360deg); }

        }



        @keyframes dataStream {

            0% { opacity: 0; transform: translateY(20px); }

            50% { opacity: 1; transform: translateY(0); }

            100% { opacity: 0; transform: translateY(-20px); }

        }



        /* Ultimate Glass Effects */

        .quantum-glass {

            background: rgba(255, 255, 255, 0.03);

            backdrop-filter: blur(25px) saturate(200%);

            border: 1px solid rgba(255, 255, 255, 0.08);

            box-shadow: 

                0 8px 32px rgba(93, 92, 222, 0.1),

                inset 0 1px 0 rgba(255, 255, 255, 0.05),

                0 0 0 1px rgba(93, 92, 222, 0.05);

        }



        .hybrid-glass {

            background: linear-gradient(135deg, 

                rgba(93, 92, 222, 0.08) 0%, 

                rgba(139, 92, 246, 0.06) 25%,

                rgba(236, 72, 153, 0.08) 50%,

                rgba(249, 115, 22, 0.06) 75%,

                rgba(6, 182, 212, 0.08) 100%);

            backdrop-filter: blur(20px) saturate(180%);

            border: 1px solid rgba(255, 255, 255, 0.1);

            position: relative;

            overflow: hidden;

        }



        .hybrid-glass::before {

            content: '';

            position: absolute;

            top: 0;

            left: -100%;

            width: 100%;

            height: 100%;

            background: linear-gradient(90deg, 

                transparent, 

                rgba(255, 255, 255, 0.1), 

                transparent);

            transition: left 0.8s;

        }



        .hybrid-glass:hover::before {

            left: 100%;

        }



        /* Neural Cards */

        .neural-card {

            background: linear-gradient(135deg, 

                rgba(93, 92, 222, 0.12) 0%, 

                rgba(139, 92, 246, 0.08) 35%,

                rgba(6, 182, 212, 0.10) 70%,

                rgba(245, 158, 11, 0.08) 100%);

            backdrop-filter: blur(18px);

            border: 1px solid rgba(93, 92, 222, 0.2);

            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);

            position: relative;

            overflow: hidden;

        }



        .neural-card::after {

            content: '';

            position: absolute;

            top: 0;

            left: 0;

            right: 0;

            bottom: 0;

            background: linear-gradient(45deg, 

                transparent 0%, 

                rgba(255, 255, 255, 0.03) 50%, 

                transparent 100%);

            opacity: 0;

            transition: opacity 0.3s;

        }



        .neural-card:hover {

            transform: translateY(-12px) scale(1.03);

            box-shadow: 

                0 25px 50px rgba(93, 92, 222, 0.25),

                0 0 80px rgba(139, 92, 246, 0.15),

                inset 0 1px 0 rgba(255, 255, 255, 0.1);

            border-color: rgba(93, 92, 222, 0.5);

        }



        .neural-card:hover::after {

            opacity: 1;

        }



        /* Holographic Buttons */

        .holographic-button {

            background: var(--hybrid-gradient);

            background-size: 400% 400%;

            animation: holographicShift 8s ease-in-out infinite;

            position: relative;

            overflow: hidden;

            border: none;

            transition: all 0.3s ease;

        }



        .holographic-button::before {

            content: '';

            position: absolute;

            top: 0;

            left: -100%;

            width: 100%;

            height: 100%;

            background: linear-gradient(90deg, 

                transparent, 

                rgba(255, 255, 255, 0.25), 

                transparent);

            transition: left 0.6s;

        }



        .holographic-button:hover {

            transform: translateY(-3px) scale(1.05);

            box-shadow: 0 15px 35px rgba(93, 92, 222, 0.3);

        }



        .holographic-button:hover::before {

            left: 100%;

        }



        /* Advanced Code Display */

        .code-display {

            background: rgba(0, 0, 0, 0.85);

            border: 1px solid rgba(93, 92, 222, 0.3);

            font-family: 'JetBrains Mono', 'Courier New', monospace;

            color: #e0e0e0;

            position: relative;

            overflow: hidden;

        }



        .code-display::before {

            content: '';

            position: absolute;

            top: 0;

            left: 0;

            right: 0;

            height: 1px;

            background: linear-gradient(90deg, 

                transparent, 

                rgba(93, 92, 222, 0.6), 

                transparent);

            animation: neuralFlow 3s linear infinite;

        }



        .code-display .keyword { color: #569cd6; font-weight: bold; }

        .code-display .string { color: #ce9178; }

        .code-display .number { color: #b5cea8; }

        .code-display .comment { color: #6a9955; font-style: italic; }

        .code-display .function { color: #dcdcaa; }

        .code-display .type { color: #4ec9b0; }



        /* Data Stream Effects */

        .data-stream {

            font-family: 'JetBrains Mono', monospace;

            color: #00ff88;

            text-shadow: 0 0 10px #00ff88;

            font-size: 11px;

            line-height: 1.3;

            animation: dataStream 3s linear infinite;

        }



        /* Quantum Particles */

        .quantum-bg {

            position: fixed;

            top: 0;

            left: 0;

            width: 100%;

            height: 100%;

            z-index: -1;

            opacity: 0.4;

        }



        /* Neural Network Elements */

        .neural-node {

            width: 6px;

            height: 6px;

            border-radius: 50%;

            background: radial-gradient(circle, #5D5CDE, #8B5CF6);

            box-shadow: 0 0 15px var(--neural-glow);

            animation: quantumPulse 4s ease-in-out infinite;

            position: absolute;

        }



        .neural-connection {

            height: 1px;

            background: linear-gradient(90deg, 

                transparent, 

                rgba(93, 92, 222, 0.4), 

                rgba(139, 92, 246, 0.6),

                rgba(93, 92, 222, 0.4),

                transparent);

            animation: neuralFlow 5s linear infinite;

            position: absolute;

        }



        /* Consciousness Meter */

        .consciousness-meter {

            position: relative;

            height: 6px;

            background: rgba(255, 255, 255, 0.1);

            border-radius: 3px;

            overflow: hidden;

        }



        .consciousness-meter::before {

            content: '';

            position: absolute;

            top: 0;

            left: 0;

            height: 100%;

            width: var(--consciousness-level, 0%);

            background: var(--hybrid-gradient);

            border-radius: 3px;

            transition: width 1.5s ease-out;

            box-shadow: 0 0 10px rgba(93, 92, 222, 0.5);

        }



        /* Ultimate Loader */

        .quantum-loader {

            width: 80px;

            height: 80px;

            position: relative;

        }



        .quantum-loader::before,

        .quantum-loader::after {

            content: '';

            position: absolute;

            border-radius: 50%;

            animation: quantumPulse 2s ease-in-out infinite;

        }

        .quantum-loader::before {

            width: 100%;

            height: 100%;

            border: 3px solid rgba(93, 92, 222, 0.3);

            border-top: 3px solid #5D5CDE;

        }

        .quantum-loader::after {

            width: 60%;

            height: 60%;

            top: 20%;

            left: 20%;

            border: 2px solid rgba(139, 92, 246, 0.4);

            border-top: 2px solid #8B5CF6;

            animation-direction: reverse;

            animation-duration: 1.5s;

        }



        /* AI Status Indicators */

        .ai-status {

            display: inline-flex;

            align-items: center;

            gap: 0.5rem;

            padding: 0.5rem 1rem;

            background: rgba(6, 182, 212, 0.1);

            border: 1px solid rgba(6, 182, 212, 0.3);

            border-radius: 2rem;

            font-size: 0.875rem;

            transition: all 0.3s ease;

        }

{

  "messages": [

    { "role": "user", "content": "What is the weather in San Francisco?" },

    {

      "role": "assistant",

      "tool_calls": [

        {

          "id": "call_id",

          "type": "function",

          "function": {

            "name": "get_current_weather",

            "arguments": "{\"location\": \"San Francisco, USA\", \"format\": \"celsius\"}"

          }

        }

      ]

    }

  ],

  "parallel_tool_calls": false,

  "tools": [

    {

      "type": "function",

      "function": {

        "name": "get_current_weather",

        "description": "Get the current weather",

        "parameters": {

          "type": "object",

          "properties": {

            "location": {

                "type": "string",

                "description": "The city and country, eg. San Francisco, USA"

            },

            "format": { "type": "string", "enum": ["celsius", "fahrenheit"] }

          },

          "required": ["location", "format"]

        }

      }

    }

  ]

}

{"messages":[{"role":"user","content":"What is the weather in San Francisco?"},{"role":"assistant","tool_calls":[{"id":"call_id","type":"function","function":{"name":"get_current_weather","arguments":"{\"location\": \"San Francisco, USA\", \"format\": \"celsius\"}"}}]}],"parallel_tool_calls":false,"tools":[{"type":"function","function":{"name":"get_current_weather","description":"Get the current weather","parameters":{"type":"object","properties":{"location":{"type":"string","description":"The city and country, eg. San Francisco, USA"},"format":{"type":"string","enum":["celsius","fahrenheit"]}},"required":["location","format"]}}}]}

{"messages":[{"role":"user","content":"What is the weather in Minneapolis?"},{"role":"assistant","tool_calls":[{"id":"call_id","type":"function","function":{"name":"get_current_weather","arguments":"{\"location\": \"Minneapolis, USA\", \"format\": \"celsius\"}"}}]}],"parallel_tool_calls":false,"tools":[{"type":"function","function":{"name":"get_current_weather","description":"Get the current weather","parameters":{"type":"object","properties":{"location":{"type":"string","description":"The city and country, eg. Minneapolis, USA"},"format":{"type":"string","enum":["celsius","fahrenheit"]}},"required":["location","format"]}}}]}

{"messages":[{"role":"user","content":"What is the weather in San Diego?"},{"role":"assistant","tool_calls":[{"id":"call_id","type":"function","function":{"name":"get_current_weather","arguments":"{\"location\": \"San Diego, USA\", \"format\": \"celsius\"}"}}]}],"parallel_tool_calls":false,"tools":[{"type":"function","function":{"name":"get_current_weather","description":"Get the current weather","parameters":{"type":"object","properties":{"location":{"type":"string","description":"The city and country, eg. San Diego, USA"},"format":{"type":"string","enum":["celsius","fahrenheit"]}},"required":["location","format"]}}}]}

{"messages":[{"role":"user","content":"What is the weather in Memphis?"},{"role":"assistant","tool_calls":[{"id":"call_id","type":"function","function":{"name":"get_current_weather","arguments":"{\"location\": \"Memphis, USA\", \"format\": \"celsius\"}"}}]}],"parallel_tool_calls":false,"tools":[{"type":"function","function":{"name":"get_current_weather","description":"Get the current weather","parameters":{"type":"object","properties":{"location":{"type":"string","description":"The city and country, eg. Memphis, USA"},"format":{"type":"string","enum":["celsius","fahrenheit"]}},"required":["location","format"]}}}]}

{"messages":[{"role":"user","content":"What is the weather in Atlanta?"},{"role":"assistant","tool_calls":[{"id":"call_id","type":"function","function":{"name":"get_current_weather","arguments":"{\"location\": \"Atlanta, USA\", \"format\": \"celsius\"}"}}]}],"parallel_tool_calls":false,"tools":[{"type":"function","function":{"name":"get_current_weather","description":"Get the current weather","parameters":{"type":"object","properties":{"location":{"type":"string","description":"The city and country, eg. Atlanta, USA"},"format":{"type":"string","enum":["celsius","fahrenheit"]}},"required":["location","format"]}}}]}

{"messages":[{"role":"user","content":"What is the weather in Sunnyvale?"},{"role":"assistant","tool_calls":[{"id":"call_id","type":"function","function":{"name":"get_current_weather","arguments":"{\"location\": \"Sunnyvale, USA\", \"format\": \"celsius\"}"}}]}],"parallel_tool_calls":false,"tools":[{"type":"function","function":{"name":"get_current_weather","description":"Get the current weather","parameters":{"type":"object","properties":{"location":{"type":"string","description":"The city and country, eg. Sunnyvale, USA"},"format":{"type":"string","enum":["celsius","fahrenheit"]}},"required":["location","format"]}}}]}

{"messages":[{"role":"user","content":"What is the weather in Chicago?"},{"role":"assistant","tool_calls":[{"id":"call_id","type":"function","function":{"name":"get_current_weather","arguments":"{\"location\": \"Chicago, USA\", \"format\": \"celsius\"}"}}]}],"parallel_tool_calls":false,"tools":[{"type":"function","function":{"name":"get_current_weather","description":"Get the current weather","parameters":{"type":"object","properties":{"location":{"type":"string","description":"The city 
