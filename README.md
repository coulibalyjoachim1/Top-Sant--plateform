import React from "react"; import { Card, CardContent } from "@/components/ui/card"; import { Button } from "@/components/ui/button"; import { Input } from "@/components/ui/input"; import { Textarea } from "@/components/ui/textarea";

export default function HomePage() { return ( <div className="min-h-screen bg-white text-gray-800"> <header className="bg-green-600 text-white p-6 text-center"> <h1 className="text-3xl font-bold">Top Santé : Santé et éducation</h1> <p className="text-sm mt-2">Apprendre la santé en français et en bambara, accessible à tous.</p> </header>

<section className="p-6 grid gap-6 md:grid-cols-2">
    <Card>
      <CardContent>
        <h2 className="text-xl font-semibold mb-2">Pourquoi Top Santé ?</h2>
        <p>
          Plateforme bilingue (français/bambara) dédiée à la santé. Accédez à des cours en vidéo et PDF sur les soins, la prévention, et plus.
        </p>
      </CardContent>
    </Card>

    <Card>
      <CardContent>
        <h2 className="text-xl font-semibold mb-2">Public visé</h2>
        <p>
          Étudiants, professionnels de santé et jeunes souhaitant renforcer leurs connaissances ou apprendre des bases solides en santé.
        </p>
      </CardContent>
    </Card>
  </section>

  <section className="p-6 bg-gray-50">
    <h2 className="text-2xl font-bold text-center mb-6">Nos cours</h2>
    <div className="grid gap-4 md:grid-cols-3">
      <Card>
        <CardContent>
          <h3 className="text-lg font-semibold">Premiers secours</h3>
          <p>Cours vidéo + PDF / FR & BM</p>
        </CardContent>
      </Card>
      <Card>
        <CardContent>
          <h3 className="text-lg font-semibold">Santé nutritionnelle</h3>
          <p>Cours PDF + quizz / FR</p>
        </CardContent>
      </Card>
      <Card>
        <CardContent>
          <h3 className="text-lg font-semibold">Hygiène et prévention</h3>
          <p>Vidéo / BM</p>
        </CardContent>
      </Card>
    </div>
  </section>

  <section className="p-6">
    <h2 className="text-2xl font-bold text-center mb-4">Témoignages</h2>
    <div className="grid gap-4 md:grid-cols-2">
      <Card>
        <CardContent>
          <p className="italic">"Grâce à Top Santé, j’ai pu réviser mes bases en santé et réussir mon concours d’entrée en école !"</p>
          <p className="mt-2 font-semibold">— Mariam, étudiante</p>
        </CardContent>
      </Card>
      <Card>
        <CardContent>
          <p className="italic">"Des cours simples et utiles, j’ai même commencé à former d’autres jeunes dans mon quartier."</p>
          <p className="mt-2 font-semibold">— Youssouf, jeune animateur</p>
        </CardContent>
      </Card>
    </div>
  </section>

  <section className="p-6 bg-green-100 text-center">
    <h2 className="text-2xl font-bold mb-4">Abonne-toi maintenant</h2>
    <p className="mb-4">Accède à tous les cours pour seulement 5000 FCFA/mois</p>
    <Button className="bg-green-600 text-white">S'abonner</Button>
  </section>

  <footer className="bg-green-700 text-white p-4 text-center">
    <p>© 2025 Top Santé | Contact : info@topsante.org</p>
  </footer>
</div>

); }

