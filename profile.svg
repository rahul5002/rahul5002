<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1180 830" width="1180" height="830">
  <defs>
    <linearGradient id="textGradient" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#7C3AED" />
      <stop offset="50%" stop-color="#22D3EE" />
      <stop offset="100%" stop-color="#10B981" />
      <animate attributeName="x1" values="0%; 50%; 0%" dur="10s" repeatCount="indefinite" />
      <animate attributeName="x2" values="100%; 150%; 100%" dur="10s" repeatCount="indefinite" />
    </linearGradient>

    <linearGradient id="asciiGradient" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#22D3EE" />
      <stop offset="100%" stop-color="#7C3AED" />
      <animate attributeName="y1" values="0%; 100%; 0%" dur="5s" repeatCount="indefinite" />
    </linearGradient>

    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="8" result="blur" />
      <feMerge>
        <feMergeNode in="blur" />
        <feMergeNode in="SourceGraphic" />
      </feMerge>
    </filter>
    <filter id="ambientBlur" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="60" />
    </filter>

    <clipPath id="typewriter">
      <rect x="0" y="0" width="0" height="40">
        <animate attributeName="width" values="0; 350; 350; 0" keyTimes="0; 0.3; 0.8; 1" dur="4s" repeatCount="indefinite" />
      </rect>
    </clipPath>

    <!-- Paint bucket flood reveal: circle grows from the bucket's position and washes color across the grid -->
    <clipPath id="paintFlood">
      <circle cx="6" cy="112" r="0">
        <animate attributeName="r" values="0;60;950;950;0" keyTimes="0;0.12;0.55;0.9;1" dur="7s" repeatCount="indefinite" calcMode="spline" keySplines="0.3 0 0.7 1;0.3 0 0.7 1;0.3 0 0.7 1;0.3 0 0.7 1" />
      </circle>
    </clipPath>
  </defs>

  <rect width="1180" height="830" fill="#030712" rx="24" />

  <circle cx="200" cy="150" r="150" fill="#7C3AED" opacity="0.15" filter="url(#ambientBlur)">
    <animateTransform attributeName="transform" type="translate" values="0,0; 30,40; 0,0" dur="15s" repeatCount="indefinite" />
  </circle>
  <circle cx="980" cy="450" r="200" fill="#10B981" opacity="0.1" filter="url(#ambientBlur)">
    <animateTransform attributeName="transform" type="translate" values="0,0; -40,-30; 0,0" dur="18s" repeatCount="indefinite" />
  </circle>

  <!-- Glassmorphism Container (Left) -->
  <rect x="40" y="40" width="410" height="530" fill="#0F172A" stroke="rgba(255,255,255,0.08)" stroke-width="1.5" rx="16" />

  <!-- Glassmorphism Container (Right Terminal) -->
  <rect x="480" y="40" width="660" height="530" fill="#0F172A" stroke="rgba(255,255,255,0.08)" stroke-width="1.5" rx="16" />

  <!-- Glassmorphism Container (Bottom - Contributions) -->
  <rect x="40" y="590" width="1100" height="200" fill="#0F172A" stroke="rgba(255,255,255,0.08)" stroke-width="1.5" rx="16" />

  <!-- LEFT SIDE: ASCII portrait rendered from photo -->
  <g transform="translate(46, 70)">
    <text x="0" y="-14" font-size="12" fill="#22D3EE" font-family="monospace" font-weight="700" letter-spacing="1">$ whoami --ascii</text>
    <g transform="translate(0, 10)" fill="url(#asciiGradient)" font-family="monospace" font-size="8.4" font-weight="700" filter="url(#glow)" style="white-space:pre">
      <animateTransform attributeName="transform" type="translate" values="0,10; 0,6; 0,10" dur="4s" repeatCount="indefinite" />
      <text x="0" y="0.0" opacity="0">::::::::::::::::::::::::::::::::::::::::::::::<animate attributeName="opacity" values="0;1" dur="0.4s" begin="0.0s" fill="freeze"/></text>
      <text x="0" y="11.6" opacity="0">::::::::::::::::::::::::::::::::::::::::::::::<animate attributeName="opacity" values="0;1" dur="0.4s" begin="0.07s" fill="freeze"/></text>
      <text x="0" y="23.2" opacity="0">::::::::::::::::::::::::::::::::::::::::::::::<animate attributeName="opacity" values="0;1" dur="0.4s" begin="0.14s" fill="freeze"/></text>
      <text x="0" y="34.8" opacity="0">::::::::::::::::::::::::::::::::::::::::::::::<animate attributeName="opacity" values="0;1" dur="0.4s" begin="0.21s" fill="freeze"/></text>
      <text x="0" y="46.4" opacity="0">:::::::::::::::::--==++++=---:::::::::::::::::<animate attributeName="opacity" values="0;1" dur="0.4s" begin="0.28s" fill="freeze"/></text>
      <text x="0" y="58.0" opacity="0">::::::::::::-==+*##%%@@@@@%%%%#*=-::::::::::::<animate attributeName="opacity" values="0;1" dur="0.4s" begin="0.35s" fill="freeze"/></text>
      <text x="0" y="69.6" opacity="0">:::::::::=*#*##*######%%@@@@@@%%%%#+-:::::::::<animate attributeName="opacity" values="0;1" dur="0.4s" begin="0.42s" fill="freeze"/></text>
      <text x="0" y="81.2" opacity="0">::::::-+#%##*########%%@@@@@@@%%%%%%#+-:::::::<animate attributeName="opacity" values="0;1" dur="0.4s" begin="0.49s" fill="freeze"/></text>
      <text x="0" y="92.8" opacity="0">::::-*%@%%%%%%%%%%%%%@@@@@@@@@@@%%@%%%%#*=::::<animate attributeName="opacity" values="0;1" dur="0.4s" begin="0.56s" fill="freeze"/></text>
      <text x="0" y="104.4" opacity="0">:::+%@@@@@@@@@%@@@@@@@@@@@@@@%%%@@%%%%%%%%=:::<animate attributeName="opacity" values="0;1" dur="0.4s" begin="0.63s" fill="freeze"/></text>
      <text x="0" y="116.0" opacity="0">::=@@@@@@@@@@@@@%%%%%%%%%%%%%%%%@@@%%%%@@%%=.:<animate attributeName="opacity" values="0;1" dur="0.4s" begin="0.7s" fill="freeze"/></text>
      <text x="0" y="127.6" opacity="0">::%@@@@%%%%%@%%##**+**+++***#%@@%%*#@@@@@@@*::<animate attributeName="opacity" values="0;1" dur="0.4s" begin="0.77s" fill="freeze"/></text>
      <text x="0" y="139.2" opacity="0">.=@@@@%#*++***+=-:::-::::--=++**+=-=#%@@@@@%-.<animate attributeName="opacity" values="0;1" dur="0.4s" begin="0.84s" fill="freeze"/></text>
      <text x="0" y="150.8" opacity="0">.+@@@@#+=---:::..........:::--------+%@%%@@@-.<animate attributeName="opacity" values="0;1" dur="0.4s" begin="0.91s" fill="freeze"/></text>
      <text x="0" y="162.4" opacity="0">.+@@@%*=--:::::::----:--==+++++++-:--+#%%@@#:.<animate attributeName="opacity" values="0;1" dur="0.4s" begin="0.98s" fill="freeze"/></text>
      <text x="0" y="174.0" opacity="0">.-%@@%+=--===+**####*+*#########**+===+%%%@*..<animate attributeName="opacity" values="0;1" dur="0.4s" begin="1.05s" fill="freeze"/></text>
      <text x="0" y="185.6" opacity="0">.:#@@#=++=++***######-=############**=-*%%%=..<animate attributeName="opacity" values="0;1" dur="0.4s" begin="1.12s" fill="freeze"/></text>
      <text x="0" y="197.2" opacity="0">..=%@#++*******##***=..=##***###****+-:-##*+..<animate attributeName="opacity" values="0;1" dur="0.4s" begin="1.19s" fill="freeze"/></text>
      <text x="0" y="208.8" opacity="0">..-#%+=-=---====-:-=:..:-=+---:------::-+**#..<animate attributeName="opacity" values="0;1" dur="0.4s" begin="1.26s" fill="freeze"/></text>
      <text x="0" y="220.4" opacity="0">:.-##+--:::.....:-::...:--=#*+=-====---=+%#*..<animate attributeName="opacity" values="0;1" dur="0.4s" begin="1.33s" fill="freeze"/></text>
      <text x="0" y="232.0" opacity="0">..:+*+=-::---=+**==++++*##*#**+==++***+==##-..<animate attributeName="opacity" values="0;1" dur="0.4s" begin="1.4s" fill="freeze"/></text>
      <text x="0" y="243.6" opacity="0">...:=+++====+*#*==#%%%%%%%%*+++**#####*+++=:..<animate attributeName="opacity" values="0;1" dur="0.4s" begin="1.47s" fill="freeze"/></text>
      <text x="0" y="255.2" opacity="0">....-=+***#***+=-:-+**#%%%#*+++*######*++*=...<animate attributeName="opacity" values="0;1" dur="0.4s" begin="1.54s" fill="freeze"/></text>
      <text x="0" y="266.8" opacity="0">....-=***###*****##########%%%#***####*+-::...<animate attributeName="opacity" values="0;1" dur="0.4s" begin="1.61s" fill="freeze"/></text>
      <text x="0" y="278.4" opacity="0">....:-=*********+======++**++*++**####*=......<animate attributeName="opacity" values="0;1" dur="0.4s" begin="1.68s" fill="freeze"/></text>
      <text x="0" y="290.0" opacity="0">.......=****++==---=++*****++===*####*+:......<animate attributeName="opacity" values="0;1" dur="0.4s" begin="1.75s" fill="freeze"/></text>
      <text x="0" y="301.6" opacity="0">........=#***+=-::::...:::---=+**###**=.......<animate attributeName="opacity" values="0;1" dur="0.4s" begin="1.82s" fill="freeze"/></text>
      <text x="0" y="313.2" opacity="0">.........+##***+=-:::::--===+#######**:.......<animate attributeName="opacity" values="0;1" dur="0.4s" begin="1.89s" fill="freeze"/></text>
      <text x="0" y="324.8" opacity="0">.......:=*#######******####%%%%%####*+=-:.....<animate attributeName="opacity" values="0;1" dur="0.4s" begin="1.96s" fill="freeze"/></text>
      <text x="0" y="336.4" opacity="0">....-+#@@#*#%%########%%%%%%%%%#####*+#@@#-...<animate attributeName="opacity" values="0;1" dur="0.4s" begin="2.03s" fill="freeze"/></text>
      <text x="0" y="348.0" opacity="0">..-#@@@@@***#%%%#########%%%%%######*+#@@@%-..<animate attributeName="opacity" values="0;1" dur="0.4s" begin="2.1s" fill="freeze"/></text>
      <text x="0" y="359.6" opacity="0">:*%@@%%@@*+**##%%%#######%%%%%######*+#@@@@%=-<animate attributeName="opacity" values="0;1" dur="0.4s" begin="2.17s" fill="freeze"/></text>
      <text x="0" y="371.2" opacity="0">%@@%#%@%*+=++**###########%%%#######*+#@@@@@%%<animate attributeName="opacity" values="0;1" dur="0.4s" begin="2.24s" fill="freeze"/></text>
      <text x="0" y="382.8" opacity="0">@@@#%@#==+===++**##########%%%#####****@@@@@@%<animate attributeName="opacity" values="0;1" dur="0.4s" begin="2.31s" fill="freeze"/></text>
      <text x="0" y="394.4" opacity="0">@%%%@+::-=====++**########%%%######***#@@@@@@@<animate attributeName="opacity" values="0;1" dur="0.4s" begin="2.38s" fill="freeze"/></text>
      <text x="0" y="406.0" opacity="0">%%%%+ ..:----===++**################*#%%@@@@@@<animate attributeName="opacity" values="0;1" dur="0.4s" begin="2.45s" fill="freeze"/></text>
    </g>
  </g>

  <!-- RIGHT SIDE: Terminal -->
  <g transform="translate(520, 100)" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif">
    <text x="0" y="0" font-size="20" fill="#94A3B8" font-weight="500">Hi 👋! I'm</text>
    <text x="0" y="40" font-size="42" fill="#F8FAFC" font-weight="800">Rahul Mankani</text>

    <g transform="translate(0, 60)">
      <text x="0" y="30" font-size="24" font-weight="700" fill="url(#textGradient)" clip-path="url(#typewriter)">
        <tspan opacity="1">B.Tech CSE Student
          <animate attributeName="opacity" values="1;0;0" keyTimes="0;0.33;1" dur="12s" repeatCount="indefinite"/>
        </tspan>
      </text>
      <text x="0" y="30" font-size="24" font-weight="700" fill="url(#textGradient)" clip-path="url(#typewriter)">
        <tspan opacity="0">Cybersecurity Enthusiast
          <animate attributeName="opacity" values="0;1;0" keyTimes="0;0.33;1" dur="12s" repeatCount="indefinite"/>
        </tspan>
      </text>
      <text x="0" y="30" font-size="24" font-weight="700" fill="url(#textGradient)" clip-path="url(#typewriter)">
        <tspan opacity="0">UPES ACM Event Head
          <animate attributeName="opacity" values="0;0;1" keyTimes="0;0.66;1" dur="12s" repeatCount="indefinite"/>
        </tspan>
      </text>
      <rect x="0" y="7" width="12" height="28" fill="#22D3EE">
        <animate attributeName="x" values="0; 290; 290; 0" keyTimes="0; 0.3; 0.8; 1" dur="4s" repeatCount="indefinite" />
        <animate attributeName="opacity" values="1;0;1" dur="0.8s" repeatCount="indefinite" />
      </rect>
    </g>

    <g transform="translate(0, 140)" font-size="16" fill="#94A3B8">
      <text x="0" y="0" opacity="0">📍 Location: Dehradun, India <animate attributeName="opacity" values="0;1" dur="0.5s" begin="1s" fill="freeze"/></text>
      <text x="0" y="35" opacity="0">🎓 Education: 3rd Year B.Tech CSE @ UPES <animate attributeName="opacity" values="0;1" dur="0.5s" begin="1.5s" fill="freeze"/></text>
      <text x="0" y="70" opacity="0">🎯 Focus: Net Defense, Pen Testing &amp; Software Eng. <animate attributeName="opacity" values="0;1" dur="0.5s" begin="2s" fill="freeze"/></text>
      <text x="0" y="105" opacity="0">✉️ Email: mankanirahul@gmail.com <animate attributeName="opacity" values="0;1" dur="0.5s" begin="2.5s" fill="freeze"/></text>
    </g>

    <g transform="translate(0, 280)">
      <text x="0" y="0" font-size="14" fill="#F8FAFC" font-weight="600" letter-spacing="2">TECH STACK</text>

      <g transform="translate(0, 20)">
        <rect width="80" height="32" rx="16" fill="#030712" stroke="rgba(255,255,255,0.1)"/>
        <text x="40" y="21" font-size="14" fill="#94A3B8" text-anchor="middle" font-weight="500">Python</text>
        <set attributeName="transform" to="scale(1.05)" begin="mouseover" end="mouseout" />
        <set attributeName="filter" to="url(#glow)" begin="mouseover" end="mouseout" />
      </g>
      <g transform="translate(95, 20)">
        <rect width="70" height="32" rx="16" fill="#030712" stroke="rgba(255,255,255,0.1)"/>
        <text x="35" y="21" font-size="14" fill="#94A3B8" text-anchor="middle" font-weight="500">Java</text>
        <set attributeName="transform" to="scale(1.05)" begin="mouseover" end="mouseout" />
        <set attributeName="filter" to="url(#glow)" begin="mouseover" end="mouseout" />
      </g>
      <g transform="translate(180, 20)">
        <rect width="60" height="32" rx="16" fill="#030712" stroke="rgba(255,255,255,0.1)"/>
        <text x="30" y="21" font-size="14" fill="#94A3B8" text-anchor="middle" font-weight="500">C</text>
        <set attributeName="transform" to="scale(1.05)" begin="mouseover" end="mouseout" />
        <set attributeName="filter" to="url(#glow)" begin="mouseover" end="mouseout" />
      </g>
      <g transform="translate(255, 20)">
        <rect width="105" height="32" rx="16" fill="#030712" stroke="rgba(255,255,255,0.1)"/>
        <text x="52.5" y="21" font-size="14" fill="#94A3B8" text-anchor="middle" font-weight="500">JavaScript</text>
        <set attributeName="transform" to="scale(1.05)" begin="mouseover" end="mouseout" />
        <set attributeName="filter" to="url(#glow)" begin="mouseover" end="mouseout" />
      </g>

      <g transform="translate(0, 65)">
        <rect width="70" height="32" rx="16" fill="#030712" stroke="rgba(255,255,255,0.1)"/>
        <text x="35" y="21" font-size="14" fill="#94A3B8" text-anchor="middle" font-weight="500">SQL</text>
        <set attributeName="transform" to="scale(1.05)" begin="mouseover" end="mouseout" />
        <set attributeName="filter" to="url(#glow)" begin="mouseover" end="mouseout" />
      </g>
      <g transform="translate(85, 65)">
        <rect width="90" height="32" rx="16" fill="#030712" stroke="rgba(255,255,255,0.1)"/>
        <text x="45" y="21" font-size="14" fill="#94A3B8" text-anchor="middle" font-weight="500">MongoDB</text>
        <set attributeName="transform" to="scale(1.05)" begin="mouseover" end="mouseout" />
        <set attributeName="filter" to="url(#glow)" begin="mouseover" end="mouseout" />
      </g>
      <g transform="translate(190, 65)">
        <rect width="100" height="32" rx="16" fill="#030712" stroke="rgba(255,255,255,0.1)"/>
        <text x="50" y="21" font-size="14" fill="#94A3B8" text-anchor="middle" font-weight="500">Kali Linux</text>
        <set attributeName="transform" to="scale(1.05)" begin="mouseover" end="mouseout" />
        <set attributeName="filter" to="url(#glow)" begin="mouseover" end="mouseout" />
      </g>
    </g>
  </g>

  <!-- BOTTOM: Contribution graph with paint-bucket flood-fill animation -->
  <g transform="translate(70, 618)">
    <text x="0" y="0" font-size="14" fill="#F8FAFC" font-weight="600" letter-spacing="2">CONTRIBUTIONS</text>

    <g transform="translate(40, 20)">
      <!-- month labels -->
      <g>
        <text x="0.0" y="0" font-size="11" fill="#8B949E">Aug</text>
      <text x="71.5" y="0" font-size="11" fill="#8B949E">Sep</text>
      <text x="143.0" y="0" font-size="11" fill="#8B949E">Oct</text>
      <text x="214.5" y="0" font-size="11" fill="#8B949E">Nov</text>
      <text x="286.0" y="0" font-size="11" fill="#8B949E">Dec</text>
      <text x="357.5" y="0" font-size="11" fill="#8B949E">Jan</text>
      <text x="429.0" y="0" font-size="11" fill="#8B949E">Feb</text>
      <text x="500.5" y="0" font-size="11" fill="#8B949E">Mar</text>
      <text x="572.0" y="0" font-size="11" fill="#8B949E">Apr</text>
      <text x="643.5" y="0" font-size="11" fill="#8B949E">May</text>
      <text x="715.0" y="0" font-size="11" fill="#8B949E">Jun</text>
      <text x="786.5" y="0" font-size="11" fill="#8B949E">Jul</text>
      <text x="858.0" y="0" font-size="11" fill="#8B949E">Aug</text>
      </g>

      <!-- day labels -->
      <text x="-32" y="26" font-size="11" fill="#8B949E">Mon</text>
      <text x="-32" y="60" font-size="11" fill="#8B949E">Wed</text>
      <text x="-32" y="95" font-size="11" fill="#8B949E">Fri</text>

      <g transform="translate(0, 14)">
        <!-- base (unfilled) grid -->
        <g>
          <rect x="0.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="0.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="0.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="0.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="0.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="0.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="0.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="16.5" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="16.5" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="16.5" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="16.5" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="16.5" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="16.5" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="16.5" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="33.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="33.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="33.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="33.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="33.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="33.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="33.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="49.5" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="49.5" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="49.5" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="49.5" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="49.5" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="49.5" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="49.5" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="66.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="66.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="66.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="66.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="66.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="66.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="66.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="82.5" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="82.5" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="82.5" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="82.5" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="82.5" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="82.5" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="82.5" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="99.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="99.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="99.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="99.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="99.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="99.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="99.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="115.5" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="115.5" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="115.5" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="115.5" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="115.5" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="115.5" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="115.5" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="132.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="132.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="132.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="132.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="132.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="132.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="132.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="148.5" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="148.5" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="148.5" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="148.5" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="148.5" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="148.5" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="148.5" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="165.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="165.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="165.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="165.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="165.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="165.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="165.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="181.5" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="181.5" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="181.5" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="181.5" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="181.5" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="181.5" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="181.5" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="198.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="198.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="198.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="198.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="198.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="198.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="198.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="214.5" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="214.5" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="214.5" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="214.5" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="214.5" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="214.5" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="214.5" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="231.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="231.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="231.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="231.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="231.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="231.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="231.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="247.5" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="247.5" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="247.5" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="247.5" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="247.5" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="247.5" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="247.5" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="264.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="264.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="264.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="264.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="264.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="264.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="264.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="280.5" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="280.5" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="280.5" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="280.5" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="280.5" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="280.5" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="280.5" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="297.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="297.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="297.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="297.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="297.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="297.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="297.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="313.5" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="313.5" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="313.5" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="313.5" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="313.5" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="313.5" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="313.5" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="330.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="330.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="330.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="330.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="330.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="330.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="330.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="346.5" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="346.5" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="346.5" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="346.5" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="346.5" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="346.5" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="346.5" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="363.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="363.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="363.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="363.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="363.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="363.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="363.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="379.5" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="379.5" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="379.5" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="379.5" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="379.5" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="379.5" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="379.5" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="396.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="396.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="396.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="396.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="396.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="396.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="396.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="412.5" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="412.5" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="412.5" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="412.5" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="412.5" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="412.5" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="412.5" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="429.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="429.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="429.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="429.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="429.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="429.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="429.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="445.5" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="445.5" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="445.5" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="445.5" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="445.5" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="445.5" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="445.5" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="462.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="462.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="462.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="462.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="462.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="462.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="462.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="478.5" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="478.5" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="478.5" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="478.5" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="478.5" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="478.5" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="478.5" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="495.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="495.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="495.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="495.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="495.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="495.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="495.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="511.5" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="511.5" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="511.5" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="511.5" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="511.5" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="511.5" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="511.5" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="528.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="528.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="528.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="528.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="528.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="528.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="528.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="544.5" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="544.5" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="544.5" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="544.5" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="544.5" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="544.5" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="544.5" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="561.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="561.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="561.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="561.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="561.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="561.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="561.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="577.5" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="577.5" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="577.5" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="577.5" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="577.5" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="577.5" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="577.5" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="594.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="594.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="594.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="594.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="594.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="594.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="594.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="610.5" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="610.5" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="610.5" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="610.5" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="610.5" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="610.5" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="610.5" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="627.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="627.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="627.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="627.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="627.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="627.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="627.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="643.5" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="643.5" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="643.5" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="643.5" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="643.5" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="643.5" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="643.5" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="660.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="660.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="660.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="660.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="660.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="660.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="660.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="676.5" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="676.5" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="676.5" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="676.5" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="676.5" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="676.5" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="676.5" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="693.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="693.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="693.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="693.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="693.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="693.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="693.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="709.5" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="709.5" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="709.5" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="709.5" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="709.5" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="709.5" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="709.5" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="726.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="726.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="726.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="726.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="726.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="726.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="726.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="742.5" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="742.5" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="742.5" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="742.5" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="742.5" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="742.5" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="742.5" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="759.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="759.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="759.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="759.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="759.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="759.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="759.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="775.5" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="775.5" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="775.5" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="775.5" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="775.5" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="775.5" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="775.5" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="792.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="792.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="792.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="792.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="792.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="792.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="792.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="808.5" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="808.5" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="808.5" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="808.5" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="808.5" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="808.5" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="808.5" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="825.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="825.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="825.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="825.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="825.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="825.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="825.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="841.5" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="841.5" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="841.5" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="841.5" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="841.5" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="841.5" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="841.5" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="858.0" y="0.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="858.0" y="16.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="858.0" y="33.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="858.0" y="49.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="858.0" y="66.0" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="858.0" y="82.5" width="13" height="13" rx="2.5" fill="#161b22"/>
      <rect x="858.0" y="99.0" width="13" height="13" rx="2.5" fill="#161b22"/>
        </g>

        <!-- colored contributions, revealed by the paint flood -->
        <g clip-path="url(#paintFlood)">
          <rect x="16.5" y="16.5" width="13" height="13" rx="2.5" fill="#26a641"/>
        <rect x="148.5" y="16.5" width="13" height="13" rx="2.5" fill="#006d32"/>
        <rect x="165.0" y="16.5" width="13" height="13" rx="2.5" fill="#0e4429"/>
        <rect x="297.0" y="16.5" width="13" height="13" rx="2.5" fill="#006d32"/>
        <rect x="429.0" y="49.5" width="13" height="13" rx="2.5" fill="#006d32"/>
        <rect x="561.0" y="82.5" width="13" height="13" rx="2.5" fill="#0e4429"/>
        <rect x="577.5" y="82.5" width="13" height="13" rx="2.5" fill="#26a641"/>
        <rect x="643.5" y="16.5" width="13" height="13" rx="2.5" fill="#26a641"/>
        <rect x="643.5" y="82.5" width="13" height="13" rx="2.5" fill="#26a641"/>
        <rect x="709.5" y="82.5" width="13" height="13" rx="2.5" fill="#006d32"/>
        <rect x="759.0" y="16.5" width="13" height="13" rx="2.5" fill="#006d32"/>
        <rect x="759.0" y="49.5" width="13" height="13" rx="2.5" fill="#0e4429"/>
        <rect x="775.5" y="16.5" width="13" height="13" rx="2.5" fill="#006d32"/>
        <rect x="825.0" y="82.5" width="13" height="13" rx="2.5" fill="#26a641"/>
        <rect x="858.0" y="16.5" width="13" height="13" rx="2.5" fill="#0e4429"/>
        <rect x="858.0" y="82.5" width="13" height="13" rx="2.5" fill="#26a641"/>
        </g>

        <!-- paint bucket + drip, synced to the flood loop -->
        <g transform="translate(-24, 108)">
          <text x="0" y="10" font-size="16">🪣
            <animateTransform attributeName="transform" type="translate" values="0,0; 0,-3; 0,0" dur="0.9s" begin="0s" repeatCount="indefinite"/>
          </text>
          <circle cx="12" cy="4" r="3" fill="#39d353" opacity="0">
            <animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.05;0.5;0.6" dur="7s" repeatCount="indefinite"/>
            <animate attributeName="cy" values="4;14;4" dur="1.4s" repeatCount="indefinite"/>
          </circle>
        </g>
      </g>
    </g>
  </g>

  <rect width="1180" height="20" fill="rgba(34, 211, 238, 0.05)" filter="url(#glow)">
    <animate attributeName="y" values="-20; 830" dur="6s" repeatCount="indefinite" />
  </rect>
</svg>
