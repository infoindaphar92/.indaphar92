

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

      <section id="apropos" className="max-w-7xl mx-auto px-6 py-16">
        <div className="grid md:grid-cols-2 gap-10 items-center">
          <div className="bg-white rounded-3xl p-8 shadow-sm border">
            <h3 className="text-3xl font-bold mb-4">À propos de nous</h3>
            <p className="text-slate-600 leading-8">
              INDAPHAR 92 est un dépôt pharmaceutique engagé dans la distribution de produits de santé avec
              sérieux, traçabilité et professionnalisme. Notre mission est de répondre aux besoins des
              pharmacies, hôpitaux, cabinets médicaux et autres structures sanitaires avec efficacité.
            </p>
          </div>
          <div className="grid grid-cols-2 gap-4">
            <div className="bg-blue-50 rounded-3xl p-6 border">
              <p className="text-3xl font-bold text-blue-900">100%</p>
              <p className="text-slate-600 mt-2">Engagement qualité</p>
            </div>
            <div className="bg-blue-50 rounded-3xl p-6 border">
              <p className="text-3xl font-bold text-blue-900">24/7</p>
              <p className="text-slate-600 mt-2">Disponibilité commerciale</p>
            </div>
            <div className="bg-blue-50 rounded-3xl p-6 border">
              <p className="text-3xl font-bold text-blue-900">+Clients</p>
              <p className="text-slate-600 mt-2">Pharmacies et hôpitaux</p>
            </div>
            <div className="bg-blue-50 rounded-3xl p-6 border">
              <p className="text-3xl font-bold text-blue-900">Fiable</p>
              <p className="text-slate-600 mt-2">Livraison et suivi</p>
            </div>
          </div>
        </div>
      </section>

      <section id="services" className="bg-white border-y">
        <div className="max-w-7xl mx-auto px-6 py-16">
          <h3 className="text-3xl font-bold text-center mb-12">Nos services</h3>
          <div className="grid md:grid-cols-3 gap-6">
            <div className="bg-slate-50 rounded-3xl p-6 shadow-sm border">
              <h4 className="text-xl font-semibold mb-3">Distribution pharmaceutique</h4>
              <p className="text-slate-600 leading-7">Approvisionnement rapide en médicaments et produits de santé pour les professionnels.</p>
            </div>
            <div className="bg-slate-50 rounded-3xl p-6 shadow-sm border">
              <h4 className="text-xl font-semibold mb-3">Livraison sécurisée</h4>
              <p className="text-slate-600 leading-7">Organisation efficace des livraisons avec respect des conditions de conservation.</p>
            </div>
            <div className="bg-slate-50 rounded-3xl p-6 shadow-sm border">
              <h4 className="text-xl font-semibold mb-3">Relation client</h4>
              <p className="text-slate-600 leading-7">Suivi commercial, disponibilité produit et assistance pour vos commandes.</p>
            </div>
          </div>
        </div>
      </section>

      <section id="produits" className="max-w-7xl mx-auto px-6 py-16">
        <h3 className="text-3xl font-bold text-center mb-12">Nos catégories de produits</h3>
        <div className="grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
          {products.map((item) => (
            <div key={item} className="bg-white rounded-3xl p-6 border shadow-sm hover:shadow-md transition">
              <div className="text-blue-900 text-lg font-semibold">{item}</div>
            </div>
          ))}
        </div>
      </section>

      <section id="contact" className="bg-blue-900 text-white">
        <div className="max-w-7xl mx-auto px-6 py-16 grid md:grid-cols-2 gap-10">
          <div>
            <h3 className="text-3xl font-bold mb-4">Contact</h3>
            <p className="text-blue-100 leading-8 mb-4">
              Contactez INDAPHAR 92 pour toute demande d’information, de partenariat ou de commande.
            </p>
            <div className="space-y-2 text-blue-50">
              <p>📍 Kinshasa, RDC</p>
              <p>📞 +243 XXX XXX XXX</p>
              <p>✉ contact@indaphar92.com</p>
            </div>
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
