export default function Indaphar92Site() {
  const products = [
    "Médicaments génériques",
    "Produits hospitaliers",
    "Consommables médicaux",
    "Parapharmacie",
    "Distribution pharmaceutique",
    "Conseil et disponibilité rapide",
  ];

  return (
    <div className="min-h-screen bg-slate-50 text-slate-900">
      <header className="bg-blue-900 text-white">
        <div className="max-w-7xl mx-auto px-6 py-5 flex items-center justify-between">
          <div>
            <h1 className="text-2xl md:text-3xl font-bold tracking-wide">INDAPHAR 92</h1>
            <p className="text-sm md:text-base text-blue-100">Dépôt Pharmaceutique</p>
          </div>
          <nav className="hidden md:flex gap-6 text-sm">
            <a href="#accueil" className="hover:text-blue-200">Accueil</a>
            <a href="#apropos" className="hover:text-blue-200">À propos</a>
            <a href="#services" className="hover:text-blue-200">Services</a>
            <a href="#produits" className="hover:text-blue-200">Produits</a>
            <a href="#contact" className="hover:text-blue-200">Contact</a>
          </nav>
        </div>
      </header>

      <section id="accueil" className="bg-gradient-to-r from-blue-950 to-blue-700 text-white">
        <div className="max-w-7xl mx-auto px-6 py-20 grid md:grid-cols-2 gap-10 items-center">
          <div>
            <p className="uppercase tracking-[0.25em] text-blue-200 text-sm mb-4">Distribution pharmaceutique</p>
            <h2 className="text-4xl md:text-6xl font-extrabold leading-tight mb-6">
              Votre partenaire de confiance en produits pharmaceutiques
            </h2>
            <p className="text-lg text-blue-100 mb-8 leading-8">
              INDAPHAR 92 assure la disponibilité, la qualité et la distribution rapide des produits
              pharmaceutiques pour pharmacies, hôpitaux, cliniques et professionnels de santé.
            </p>
            <div className="flex flex-wrap gap-4">
              <a href="#contact" className="bg-white text-blue-900 px-6 py-3 rounded-2xl font-semibold shadow-lg hover:scale-105 transition">
                Nous contacter
              </a>
              <a href="#produits" className="border border-white px-6 py-3 rounded-2xl font-semibold hover:bg-white/10 transition">
                Voir nos produits
              </a>
            </div>
          </div>

          <div>
            <div className="bg-white/10 backdrop-blur rounded-3xl p-8 shadow-2xl border border-white/20">
              <h3 className="text-2xl font-bold mb-4">Pourquoi choisir INDAPHAR 92 ?</h3>
              <ul className="space-y-3 text-blue-50">
                <li>✔ Produits fiables et conformes</li>
                <li>✔ Service rapide et professionnel</li>
                <li>✔ Réseau de distribution efficace</li>
                <li>✔ Accompagnement des pharmacies et structures de santé</li>
              </ul>
            </div>
          </div>
        </div>
      </section>

          </div>
          <div className="bg-white text-slate-900 rounded-3xl p-8 shadow-xl">
            <h4 className="text-2xl font-bold mb-4">Demande rapide</h4>
            <div className="space-y-4">
              <input className="w-full border rounded-2xl px-4 py-3" placeholder="Nom complet" />
              <input className="w-full border rounded-2xl px-4 py-3" placeholder="Téléphone" />
              <input className="w-full border rounded-2xl px-4 py-3" placeholder="Email" />
              <textarea className="w-full border rounded-2xl px-4 py-3 h-32" placeholder="Votre message"></textarea>
              <button className="w-full bg-blue-900 text-white py-3 rounded-2xl font-semibold hover:opacity-90 transition">
                Envoyer
              </button>
            </div>
          </div>
        </div>
      </section>

      <footer className="bg-slate-950 text-slate-300 text-center py-6 text-sm">
        © 2026 INDAPHAR 92 - Dépôt Pharmaceutique. Tous droits réservés.
      </footer>
    </div>
  );
}
