<!DOCTYPE html>
<html>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="./dist/output.css" rel="stylesheet">
</head>

<body>

    <body class="bg-[#121417] flex items-center justify-center min-h-screen font-sans antialiased">

        <!-- Panel Principal -->
        <div class="bg-[#212428] w-[320px] p-8 rounded-[2.5rem] shadow-2xl border border-gray-800/50">

            <!-- Logo Factory OS -->
            <div class="flex items-center justify-center gap-2 mb-4">
                <svg class="w-5 h-5 text-[#4ade80]" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                        d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z">
                    </path>
                    <circle cx="12" cy="12" r="3"></circle>
                </svg>
                <span class="text-[#4ade80] font-bold tracking-[0.2em] text-xs">FACTORY OS</span>
            </div>

            <h1 class="text-white text-center font-bold text-xl mb-8 tracking-tight">MACHINE 3: STATUS</h1>

            <!-- Botón OPERATIONAL -->
            <div
                class="bg-gradient-to-r from-[#2d5a3d] to-[#1e3b29] rounded-2xl p-5 flex items-center justify-center gap-3 mb-5 shadow-inner cursor-pointer hover:opacity-90 transition-opacity">
                <div class="border-2 border-white/40 rounded-full p-1">
                    <svg class="w-4 h-4 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7"></path>
                    </svg>
                </div>
                <span class="text-white font-bold text-sm tracking-widest">OPERATIONAL</span>
            </div>

            <!-- Tarjeta UPTIME (Azul) -->
            <div
                class="bg-gradient-to-br from-[#38bdf8] to-[#1e40af] rounded-2xl p-6 mb-5 relative group cursor-default">
                <h2 class="text-white text-3xl font-extrabold">98.5%</h2>
                <p class="text-sky-100 text-[10px] font-bold uppercase tracking-wider mt-1 opacity-80">Uptime Today</p>
                <div class="absolute bottom-4 right-5 text-sky-200/40">
                    <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 12l3-3 3 3 4-4">
                        </path>
                    </svg>
                </div>
            </div>

            <!-- Tarjeta CYCLE TIME (Rojo/Naranja) -->
            <div
                class="bg-gradient-to-br from-[#f87171] to-[#7f1d1d] rounded-2xl p-6 mb-10 relative group cursor-default">
                <h2 class="text-white text-3xl font-extrabold">15.3s</h2>
                <p class="text-red-100 text-[10px] font-bold uppercase tracking-wider mt-1 opacity-80">Cycle Time</p>
                <div class="absolute bottom-4 right-5 text-red-200/40 rotate-180">
                    <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 12l3-3 3 3 4-4">
                        </path>
                    </svg>
                </div>
            </div>

            <!-- Sección de Alertas -->
            <div class="px-1">
                <p class="text-gray-500 text-[10px] font-black mb-4 uppercase tracking-[0.15em]">Live Alerts</p>
                <ul class="space-y-3">
                    <li class="flex items-center text-[#ee6c4d] text-[11px] font-bold gap-3">
                        <span
                            class="flex items-center justify-center border border-[#ee6c4d] rounded-full w-4 h-4 text-[10px]">!</span>
                        EMERGENCY STOP
                    </li>
                    <li class="flex items-center text-[#ee6c4d] text-[11px] font-bold gap-3">
                        <span
                            class="flex items-center justify-center border border-[#ee6c4d] rounded-full w-4 h-4 text-[10px]">!</span>
                        MATERIAL FEED: <span class="font-normal opacity-80 ml-[-4px]">Low</span>
                    </li>
                    <li class="flex items-center text-[#ee6c4d] text-[11px] font-bold gap-3">
                        <span
                            class="flex items-center justify-center border border-[#ee6c4d] rounded-full w-4 h-4 text-[10px]">!</span>
                        TEMPERATURE CRITICAL
                    </li>
                </ul>
            </div>

        </div>

    </body>


</body>






</html>
