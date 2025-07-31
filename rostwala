import { Button } from "./components/ui/button";
import { Card, CardContent } from "./components/ui/card";
import { Badge } from "./components/ui/badge";
import { Star, Heart, Zap, Leaf, Users, Instagram } from "lucide-react";
import roastwalLogo from "figma:asset/98a44306fcbe7f04de6f93fc9d2dbc792967a562.png";
import pudinaChanaChaatkara from "figma:asset/1e7e0fe20591e936cafe85fd01fb705af338c2a6.png";
import chatpataMix from "figma:asset/33f2deaeccd0419dbbf2b951f27e466c3ea4c00c.png";
import roastedSoyaChips from "figma:asset/254d15d400f922128e65676ed1edb76df9dc6afc.png";
import moongChanaJorGaram from "figma:asset/fb6bb64fbacedb357c83a2184a514186f44c5400.png";

export default function App() {
  const snacks = [
    {
      name: "Roasted Soya Chips",
      tagline: "Crunch with kaunch!",
      color: "bg-yellow-400",
      icon: "🌟",
      image: roastedSoyaChips
    },
    {
      name: "Pudina Chana Chaatkara",
      tagline: "Minty magic, munchy mood.",
      color: "bg-green-400",
      icon: "🌿",
      image: pudinaChanaChaatkara
    },
    {
      name: "Chatpata Mix",
      tagline: "Masaledaar mix, full desi fix.",
      color: "bg-red-400",
      icon: "🌶️",
      image: chatpataMix
    },
    {
      name: "Moong-Chana Jor Garam",
      tagline: "Street-style, ghar-jaisa zayka!",
      color: "bg-orange-400",
      icon: "🔥",
      image: moongChanaJorGaram
    }
  ];

  const benefits = [
    {
      icon: <Zap className="w-8 h-8" />,
      title: "Roasted, never fried",
      description: "Healthier cooking method"
    },
    {
      icon: <Leaf className="w-8 h-8" />,
      title: "Real ingredients, real flavor",
      description: "No artificial nonsense"
    },
    {
      icon: <Heart className="w-8 h-8" />,
      title: "100% desi delight",
      description: "Authentic Indian taste"
    }
  ];

  return (
    <div className="min-h-screen bg-gradient-to-br from-yellow-50 to-orange-50">
      {/* Header */}
      <header className="bg-white shadow-sm">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4">
          <div className="flex items-center justify-between">
            <div className="flex items-center space-x-4">
              <img src={roastwalLogo} alt="ROASTWALA Logo" className="h-16 w-16 rounded-full" />
              <div>
                <h1 className="text-2xl font-bold text-gray-900">ROASTWALA</h1>
                <p className="text-sm text-red-600 font-medium">FRY KO BYE!</p>
              </div>
            </div>
            <Button 
              className="bg-red-600 hover:bg-red-700 text-white px-6 py-2 rounded-full font-medium"
              onClick={() => window.open('https://www.instagram.com/roastwala.namkeen/', '_blank')}
            >
              Shop Now
            </Button>
          </div>
        </div>
      </header>

      {/* Hero Section */}
      <section className="relative overflow-hidden bg-gradient-to-r from-red-500 via-orange-500 to-yellow-500 py-20">
        <div className="absolute inset-0 bg-black/10"></div>
        <div className="relative max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
          <div className="mb-8">
            <h1 className="text-4xl md:text-6xl font-bold text-white mb-4 drop-shadow-lg">
              FRY KO BYE!
            </h1>
            <h2 className="text-2xl md:text-3xl font-bold text-white mb-2">
              Desi Snacks, Zero Regret.
            </h2>
            <p className="text-lg md:text-xl text-white/90 max-w-2xl mx-auto">
              Roasted, not fried. Flavorful, guilt-free, full desi swag.
            </p>
          </div>
          <Button 
            className="bg-white text-red-600 hover:bg-gray-100 px-8 py-4 text-lg font-bold rounded-full shadow-lg transform transition hover:scale-105"
            onClick={() => window.open('https://www.instagram.com/roastwala.namkeen/', '_blank')}
          >
            Shop Now
          </Button>
        </div>
      </section>

      {/* Featured Snacks */}
      <section className="py-20 bg-white">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="text-center mb-16">
            <h2 className="text-3xl md:text-4xl font-bold text-gray-900 mb-4">
              Featured Snacks
            </h2>
            <p className="text-lg text-gray-600">
              Discover our most loved desi treats
            </p>
          </div>
          
          <div className="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
            {snacks.map((snack, index) => (
              <Card key={index} className="overflow-hidden transform transition hover:scale-105 hover:shadow-xl">
                {snack.image ? (
                  <div className="h-48 bg-gray-50 flex items-center justify-center p-4">
                    <img 
                      src={snack.image} 
                      alt={snack.name}
                      className="w-full h-full object-contain"
                    />
                  </div>
                ) : (
                  <div className={`${snack.color} h-48 flex items-center justify-center`}>
                    <span className="text-4xl">{snack.icon}</span>
                  </div>
                )}
                <CardContent className="p-6 text-center">
                  <h3 className="text-lg font-bold text-gray-900 mb-2">
                    {snack.name}
                  </h3>
                  <p className="text-sm text-gray-600 italic">
                    "{snack.tagline}"
                  </p>
                  <Button 
                    className="mt-4 bg-gray-800 hover:bg-gray-900 text-white rounded-full px-4 py-2"
                    onClick={() => window.open('https://www.instagram.com/roastwala.namkeen/', '_blank')}
                  >
                    Try Now
                  </Button>
                </CardContent>
              </Card>
            ))}
          </div>
        </div>
      </section>

      {/* Why Choose Roastwala */}
      <section className="py-20 bg-gray-50">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="text-center mb-16">
            <h2 className="text-3xl md:text-4xl font-bold text-gray-900 mb-4">
              Why Choose Roastwala?
            </h2>
            <p className="text-lg text-gray-600">
              The healthy way to snack desi
            </p>
          </div>
          
          <div className="grid md:grid-cols-3 gap-8">
            {benefits.map((benefit, index) => (
              <div key={index} className="text-center">
                <div className="bg-white w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4 shadow-lg text-red-600">
                  {benefit.icon}
                </div>
                <h3 className="text-xl font-bold text-gray-900 mb-2">
                  {benefit.title}
                </h3>
                <p className="text-gray-600">
                  {benefit.description}
                </p>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* Social Proof */}
      <section className="py-20 bg-gradient-to-r from-yellow-400 to-orange-400">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
          <div className="mb-8">
            <h2 className="text-3xl font-bold text-white mb-4">
              #Roastwala
            </h2>
            <div className="flex justify-center items-center space-x-2 mb-4">
              {[...Array(5)].map((_, i) => (
                <Star key={i} className="w-6 h-6 text-white fill-current" />
              ))}
            </div>
            <p className="text-lg text-white/90 max-w-2xl mx-auto italic">
              "Finally, snacks that don't make me feel guilty! The pudina chana is my absolute favorite - it's like having street food at home but healthier!"
            </p>
            <p className="text-white/80 mt-2">- @snackqueen_mumbai</p>
          </div>
          
          <div className="flex justify-center space-x-8">
            <div className="text-center">
              <div className="text-2xl font-bold text-white">50K+</div>
              <div className="text-white/80">Happy Customers</div>
            </div>
            <div className="text-center">
              <div className="text-2xl font-bold text-white">1M+</div>
              <div className="text-white/80">Snacks Sold</div>
            </div>
            <div className="text-center">
              <div className="text-2xl font-bold text-white">4.8/5</div>
              <div className="text-white/80">Rating</div>
            </div>
          </div>
        </div>
      </section>

      {/* Footer */}
      <footer className="bg-gray-900 text-white py-12">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="text-center">
            <div className="flex items-center justify-center space-x-4 mb-6">
              <img src={roastwalLogo} alt="ROASTWALA Logo" className="h-16 w-16 rounded-full" />
              <div>
                <h1 className="text-2xl font-bold">ROASTWALA</h1>
                <p className="text-red-400 font-medium">FRY KO BYE!</p>
              </div>
            </div>
            
            <div className="mb-6">
              <p className="text-gray-300 mb-4">
                Follow us for daily doses of healthy desi snacking!
              </p>
              <div className="flex justify-center items-center space-x-2">
                <Instagram className="w-5 h-5 text-pink-400" />
                <a 
                  href="https://www.instagram.com/roastwala.namkeen/" 
                  target="_blank" 
                  rel="noopener noreferrer" 
                  className="text-pink-400 hover:text-pink-300 font-medium"
                >
                  @roastwala.namkeen
                </a>
              </div>
            </div>
            
            <div className="border-t border-gray-700 pt-6">
              <p className="text-gray-400 text-sm">
                © 2025 ROASTWALA. All rights reserved. | Made with ❤️ for desi snack lovers
              </p>
            </div>
          </div>
        </div>
      </footer>
    </div>
  );
}
