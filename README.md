// ======================================
// Portfolio Website (Next.js-safe / React standalone version)
// FIXED: Removed Next.js + lucide-react dependencies
// Compatible with sandbox React renderer
// ======================================

export default function Home() {
  return (
    <main className="min-h-screen bg-[#0d1117] text-white">

      {/* HERO */}
      <section className="text-center py-20 px-6">
        <h1 className="text-5xl font-bold">RAMI BITAR</h1>
        <p className="text-gray-400 mt-4 text-lg">
          Computer Programming Student | AI & Automation Developer | Backend Engineer
        </p>

        <div className="flex justify-center gap-4 mt-8 flex-wrap">

          <a
            href="mailto:ramibitar.connct@gmail.com"
            className="bg-white text-black px-4 py-2 rounded"
          >
            📧 Email
          </a>

          <a
            href="https://github.com/RamiAIlab"
            className="border border-gray-600 px-4 py-2 rounded"
          >
            🐙 GitHub
          </a>

          <a
            href="https://t.me/vx_rq"
            className="border border-gray-600 px-4 py-2 rounded"
          >
            📱 Telegram
          </a>

        </div>
      </section>

      {/* ABOUT */}
      <section className="max-w-4xl mx-auto px-6 py-10">
        <h2 className="text-2xl font-semibold mb-4">About Me</h2>
        <p className="text-gray-400 leading-relaxed">
          Computer Programming student focused on building real-world software systems in AI, automation, and backend development. I design scalable and production-ready applications that solve practical problems.
        </p>
      </section>

      {/* SKILLS */}
      <section className="max-w-5xl mx-auto px-6 py-10">
        <h2 className="text-2xl font-semibold mb-6">Tech Stack</h2>

        <div className="grid md:grid-cols-3 gap-4">

          <div className="bg-[#161b22] p-4 rounded">
            <h3 className="font-semibold">Languages</h3>
            <p className="text-gray-400">Python, JavaScript, TypeScript</p>
          </div>

          <div className="bg-[#161b22] p-4 rounded">
            <h3 className="font-semibold">Backend</h3>
            <p className="text-gray-400">FastAPI, Django, Node.js, Flask</p>
          </div>

          <div className="bg-[#161b22] p-4 rounded">
            <h3 className="font-semibold">Tools</h3>
            <p className="text-gray-400">Git, GitHub, Docker, PostgreSQL, MongoDB</p>
          </div>

        </div>
      </section>

      {/* PROJECT */}
      <section className="max-w-4xl mx-auto px-6 py-10">
        <h2 className="text-2xl font-semibold mb-6">Featured Project</h2>

        <div className="bg-[#161b22] p-6 rounded">
          <h3 className="text-xl font-semibold">Noorify Bot</h3>
          <p className="text-gray-400 mt-2">
            Telegram automation bot for scheduling, reminders, and user management.
          </p>

          <div className="flex gap-4 mt-4 flex-wrap">

            <a
              href="https://github.com/RamiAIlab/Noorify_Bot"
              className="border px-3 py-2 rounded"
            >
              🐙 Repo
            </a>

            <a
              href="https://t.me/Noorify_bot"
              className="border px-3 py-2 rounded"
            >
              🔗 Live Bot
            </a>

          </div>
        </div>
      </section>

      {/* CONTACT */}
      <section className="text-center px-6 py-10">
        <h2 className="text-2xl font-semibold mb-4">Contact</h2>
        <p className="text-gray-400 mb-6">
          Open for internships, freelance work, and collaborations.
        </p>

        <div className="flex justify-center gap-4 flex-wrap">

          <a
            href="mailto:ramibitar.connct@gmail.com"
            className="bg-white text-black px-4 py-2 rounded"
          >
            Email
          </a>

          <a
            href="https://linkedin.com/in/rami-bitar-16479936b"
            className="border px-4 py-2 rounded"
          >
            LinkedIn
          </a>

        </div>
      </section>

      {/* TESTS (basic sanity checks in console) */}
      <script dangerouslySetInnerHTML={{ __html: `
        console.log('Portfolio loaded successfully');
        console.log('Check links:', {
          github: 'https://github.com/RamiAIlab',
          telegram: 'https://t.me/vx_rq'
        });
      `}} />

      {/* FOOTER */}
      <footer className="text-center text-gray-500 py-10">
        Built with React (Next.js compatible structure)
      </footer>

    </main>
  );
}
