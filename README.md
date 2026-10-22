# DragonSlayer

We built a tool that generates radiology reports ~5x faster than PowerScribe. We also built RadReportBench, a benchmark that measures an AI’s ability to generate signable radiology reports from real dictations in a single shot.

## Introduction

Radiology is a profession near and dear to my heart. Both my parents are radiologists. My grandmother was a radiologist, and I spent most of my childhood in the radiology center my grandfather owned.

Over the decades, I’ve seen the radiology industry fall apart for patients and for doctors.

My dad used to serve his patients. He put on his scrubs, showed up to his practice, read cases and walked patients through their findings with love and care. Now, radiologists are shoved into small dark rooms, get lousy tech, and for process efficiency’s sake, they crunch reports while others share the news with patients.

Our deep dive into the field made me realize radiology looks a lot like coding did ~12 months ago, when putting AI in the loop made us 10x more productive and prolific.

The same way good engineers now spend far more time talking to customers and working on only the hardest problems, radiologists should be able to spend far more time with patients and still read an order of magnitude more cases. Hopefully, that leads to a world where people have access to cheaper and more frequent imaging.

We were surprised to find that a large part of the bottleneck preventing this future is purely technical.

Three big buckets of innovations are required. First, AI needs to be able to read medical imaging with more 9’s of reliability (from 9x.xx% to 99.999%). Second, we need delightful and ubiquitous imaging hardware (rooting for you, David Holz!). Lastly, we need to automate image reporting. Incredible teams are working on the first two.

DragonSlayer is focused on the third bucket. If you’re deep in AI, you will be saddened to learn what the current state of the art looks like in radiology.
