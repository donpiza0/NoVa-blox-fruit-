export default function NovaBloxFruitWebsite() { return ( <div className="min-h-screen bg-gradient-to-b from-black via-slate-900 to-blue-950 text-white font-sans"> {/* Hero Section */} <section className="flex flex-col items-center justify-center text-center px-6 py-24"> <div className="bg-blue-500/20 border border-blue-400 px-4 py-1 rounded-full text-sm mb-6 shadow-lg"> ⚡ Nova BloxFruit Community </div>

<h1 className="text-5xl md:text-7xl font-extrabold tracking-wide mb-6">
      Welcome To <span className="text-blue-400">Nova</span>
    </h1>

    <p className="max-w-2xl text-lg text-gray-300 mb-8 leading-relaxed">
      Join the ultimate BloxFruit community! Trade fruits, find raid teams,
      level up faster, and become one of the strongest pirates on the sea.
    </p>

    <div className="flex flex-wrap gap-4 justify-center">
      <button className="bg-blue-500 hover:bg-blue-600 transition px-8 py-3 rounded-2xl text-lg font-bold shadow-xl">
        Join Discord
      </button>

      <button className="border border-white/30 hover:bg-white/10 transition px-8 py-3 rounded-2xl text-lg font-bold">
        Explore Crew
      </button>
    </div>
  </section>

  {/* Features */}
  <section className="px-6 py-16 max-w-6xl mx-auto grid md:grid-cols-3 gap-8">
    <div className="bg-white/5 border border-white/10 rounded-3xl p-8 shadow-2xl backdrop-blur-md hover:scale-105 transition">
      <div className="text-4xl mb-4">🍎</div>
      <h2 className="text-2xl font-bold mb-3">Fruit Trading</h2>
      <p className="text-gray-300">
        Trade legendary fruits safely with trusted community members.
      </p>
    </div>

    <div className="bg-white/5 border border-white/10 rounded-3xl p-8 shadow-2xl backdrop-blur-md hover:scale-105 transition">
      <div className="text-4xl mb-4">⚔️</div>
      <h2 className="text-2xl font-bold mb-3">Raids & PvP</h2>
      <p className="text-gray-300">
        Find teammates for raids, boss fights, and intense PvP battles.
      </p>
    </div>

    <div className="bg-white/5 border border-white/10 rounded-3xl p-8 shadow-2xl backdrop-blur-md hover:scale-105 transition">
      <div className="text-4xl mb-4">👑</div>
      <h2 className="text-2xl font-bold mb-3">Community Events</h2>
      <p className="text-gray-300">
        Participate in giveaways, tournaments, and special crew events.
      </p>
    </div>
  </section>

  {/* Stats */}
  <section className="py-16 px-6">
    <div className="max-w-5xl mx-auto grid grid-cols-2 md:grid-cols-4 gap-6 text-center">
      <div className="bg-blue-500/10 rounded-3xl p-6 border border-blue-400/20">
        <h3 className="text-4xl font-extrabold text-blue-400">5K+</h3>
        <p className="text-gray-300 mt-2">Members</p>
      </div>

      <div className="bg-blue-500/10 rounded-3xl p-6 border border-blue-400/20">
        <h3 className="text-4xl font-extrabold text-blue-400">24/7</h3>
        <p className="text-gray-300 mt-2">Active Chat</p>
      </div>

      <div className="bg-blue-500/10 rounded-3xl p-6 border border-blue-400/20">
        <h3 className="text-4xl font-extrabold text-blue-400">100+</h3>
        <p className="text-gray-300 mt-2">Daily Trades</p>
      </div>

      <div className="bg-blue-500/10 rounded-3xl p-6 border border-blue-400/20">
        <h3 className="text-4xl font-extrabold text-blue-400">∞</h3>
        <p className="text-gray-300 mt-2">Adventure</p>
      </div>
    </div>
  </section>

  {/* Footer */}
  <footer className="border-t border-white/10 mt-10 py-8 text-center text-gray-400">
    <p>© 2026 Nova BloxFruit Community — All Rights Reserved.</p>
  </footer>
</div>

); }
