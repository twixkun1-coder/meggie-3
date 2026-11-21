import { createFileRoute } from "@tanstack/react-router";
import { AnimatePresence, MotionConfig } from "framer-motion";
import { useEffect, useState } from "react";

import { EnvelopeIntro } from "@/components/anniversary/EnvelopeIntro";
import { FloatingHearts } from "@/components/anniversary/FloatingHearts";
import { Footer } from "@/components/anniversary/Footer";
import { Hero } from "@/components/anniversary/Hero";
import { HugProvider } from "@/components/anniversary/Hugs";
import { Letter } from "@/components/anniversary/Letter";
import { Photos } from "@/components/anniversary/Photos";
import { Story } from "@/components/anniversary/Story";
import { Song } from "@/components/anniversary/Song";
import { HER_NAME } from "@/content/anniversary";

const TITLE = `Happy 2nd Anniversary, ${HER_NAME} ♥`;
const DESCRIPTION = "Two years with you, and I'd choose you again every single day.";

export const Route = createFileRoute("/")({
  head: () => ({
    meta: [
      { title: TITLE },
      { name: "description", content: DESCRIPTION },
      { property: "og:title", content: TITLE },
      { property: "og:description", content: DESCRIPTION },
      { property: "og:type", content: "website" },
      { name: "twitter:card", content: "summary_large_image" },
    ],
  }),
  component: Index,
});

function Index() {
  const [opened, setOpened] = useState(false);

  useEffect(() => {
    document.body.style.overflow = opened ? "" : "hidden";
    return () => {
      document.body.style.overflow = "";
    };
  }, [opened]);

  return (
    <MotionConfig reducedMotion="user">
      <HugProvider>
        <FloatingHearts />
        <main className="relative z-10 overflow-x-hidden">
          <Hero revealed={opened} />
          <Story />
          <Photos />
          <Letter />
          <Song />
          <Footer />
        </main>
        <AnimatePresence>
          {!opened && <EnvelopeIntro key="intro" name={HER_NAME} onDone={() => setOpened(true)} />}
        </AnimatePresence>
      </HugProvider>
    </MotionConfig>
  );
}
