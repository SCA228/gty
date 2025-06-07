import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { CloudRain, BookOpenText, Users, Mail } from "lucide-react";
import { motion } from "framer-motion";

export default function RainyDayResearch() {
  return (
    <main className="min-h-screen bg-gradient-to-br from-blue-100 to-gray-200 p-6">
      <motion.h1
        className="text-4xl font-bold text-center text-blue-900 mb-10"
        initial={{ opacity: 0, y: -50 }}
        animate={{ opacity: 1, y: 0 }}
      >
        <CloudRain className="inline-block mr-2" /> Rainy Day Research
      </motion.h1>

      <section className="grid md:grid-cols-3 gap-6 mb-10">
        <Card>
          <CardContent className="p-4">
            <BookOpenText className="text-blue-700 mb-2" />
            <h2 className="text-xl font-semibold mb-1">Our Articles</h2>
            <p>Explore findings on how rain affects productivity, mood, and urban life.</p>
          </CardContent>
        </Card>
        <Card>
          <CardContent className="p-4">
            <Users className="text-blue-700 mb-2" />
            <h2 className="text-xl font-semibold mb-1">Meet the Team</h2>
            <p>Get to know the minds behind our cozy climate-driven research projects.</p>
          </CardContent>
        </Card>
        <Card>
          <CardContent className="p-4">
            <Mail className="text-blue-700 mb-2" />
            <h2 className="text-xl font-semibold mb-1">Contact Us</h2>
            <p>Have questions or want to collaborate? We’d love to hear from you.</p>
          </CardContent>
        </Card>
      </section>

      <section className="text-center">
        <Button className="bg-blue-600 hover:bg-blue-700 text-white px-6 py-2 rounded-full">
          Read Our Latest Report
        </Button>
      </section>
    </main>
  );
}
