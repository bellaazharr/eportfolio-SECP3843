# Reflection — Web Crawling Project (Mudah.my)

## Objective
Build a working web crawler for a real, actively-maintained website, applying high-performance data processing principles to large-scale data collection.

## What I Did
As group lead, I was responsible for crawling the Vehicles and Property categories, along with writing the report's introduction and system design sections. Early attempts used BeautifulSoup and Selenium, but both proved unreliable against the live site's structure.

## What Was Difficult
The real turning point was realizing that fighting the rendered HTML wasn't the right approach at all. Once I found that Mudah.my's search functionality was backed by an internal API, switching to calling that API directly was both simpler and far more stable than anything BeautifulSoup or Selenium could achieve.

## How This Connects to Course Objectives
This is a direct lesson in high-performance data processing: the "high performance" part isn't only about code optimization, it's also about choosing the right extraction method in the first place. An API call is inherently more efficient and reliable than rendering and parsing a full webpage.

## What I'd Do Differently
I'd check for an internal API earlier in the process, rather than treating it as a fallback after BeautifulSoup/Selenium failed — it would have saved significant debugging time.
