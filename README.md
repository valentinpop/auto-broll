# Auto-B-Roll 🎬🤖  

*AI-powered assistant that combs through your B-roll, rejects shaky/blurred footage, and delivers a ready-to-edit “B-roll selects” timeline (Premiere XML / Resolve EDL).*  

## Why  
Manually skimming hours of B-roll is painful. Auto-B-Roll uses computer-vision heuristics (blur, shakiness, exposure) and CLIP content tagging to keep only strong, stable 2-second chunks.  

## MVP roadmap  
1. Core engine — blur & shake detection → JSON segments  
2. XML / EDL exporter → import into NLE  
3. Desktop UI (Tauri) + NLE bridge scripts  
4. Tagging & scoring; full UX polish  

**25 fps time-base by default** • **Audio ignored** • **MIT-licensed**  
