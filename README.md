import React from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";

export default function TemplyHome() {
  return (
    <div className="min-h-screen bg-gradient-to-br from-gray-900 via-gray-800 to-gray-900 text-white p-6">
      <header className="text-center mb-12">
        <h1 className="text-5xl font-bold tracking-tight">Temply</h1>
        <p className="text-lg mt-4 text-gray-400">Download free & premium design templates to flex your style</p>
      </header>

      <section className="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6">
        <Card>
          <CardContent className="p-4">
            <h2 className="text-xl font-semibold mb-2">Instagram Posts</h2>
            <p className="text-sm text-gray-300">Creative post templates to stand out on the feed.</p>
            <Button className="mt-4 w-full">Explore</Button>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="p-4">
            <h2 className="text-xl font-semibold mb-2">Stories</h2>
            <p className="text-sm text-gray-300">Stunning story designs to make your audience tap through.</p>
            <Button className="mt-4 w-full">Explore</Button>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="p-4">
            <h2 className="text-xl font-semibold mb-2">Wallpapers</h2>
            <p className="text-sm text-gray-300">Minimal, vibrant or dark-mode wallpapers for any device.</p>
            <Button className="mt-4 w-full">Explore</Button>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="p-4">
            <h2 className="text-xl font-semibold mb-2">Posters</h2>
            <p className="text-sm text-gray-300">Editable posters for online or print use.</p>
            <Button className="mt-4 w-full">Explore</Button>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="p-4">
            <h2 className="text-xl font-semibold mb-2">Canva Templates</h2>
            <p className="text-sm text-gray-300">Templates you can edit directly in Canva.</p>
            <Button className="mt-4 w-full">Explore</Button>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="p-4">
            <h2 className="text-xl font-semibold mb-2">Premium Zone</h2>
            <p className="text-sm text-gray-300">Exclusive packs and bundles for loyal creators.</p>
            <Button className="mt-4 w-full">Unlock</Button>
          </CardContent>
        </Card>
      </section>
    </div>
  );
}
