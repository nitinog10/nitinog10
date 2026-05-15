<div align="center">

```aura width=850 height=800
<div style={{ display: 'flex', flexDirection: 'column', padding: '48px 56px', width: '100%', height: '100%', backgroundColor: '#09090b', borderRadius: 24, border: '1px solid #27272a', position: 'relative', overflow: 'hidden', fontFamily: 'Inter, sans-serif' }}>
  
  {/* Dynamic Aura Backgrounds */}
  <div style={{ position: 'absolute', top: -100, right: -100, width: 600, height: 600, backgroundImage: 'radial-gradient(circle, rgba(168, 85, 247, 0.15) 0%, rgba(0,0,0,0) 70%)' }} />
  <div style={{ position: 'absolute', bottom: -150, left: -100, width: 700, height: 700, backgroundImage: 'radial-gradient(circle, rgba(45, 212, 191, 0.15) 0%, rgba(0,0,0,0) 70%)' }} />

  {/* Hero Header */}
  <div style={{ display: 'flex', flexDirection: 'row', alignItems: 'center', marginBottom: 48, zIndex: 10 }}>
    <img src="https://avatars.githubusercontent.com/u/102604629?v=4" style={{ width: 120, height: 120, borderRadius: 100, border: '2px solid rgba(255, 255, 255, 0.1)' }} />
    <div style={{ display: 'flex', flexDirection: 'column', marginLeft: 36 }}>
      <div style={{ color: 'white', fontSize: 36, fontWeight: 800, letterSpacing: -0.5 }}>Nitin Mishra</div>
      <div style={{ color: '#a1a1aa', fontSize: 15, marginTop: 8 }}>Gen AI Architect SDE Intern @entoplearning | Building @docuverseAI</div>
      <div style={{ display: 'flex', gap: 12, marginTop: 16 }}>
        <div style={{ padding: '6px 16px', backgroundColor: 'rgba(24, 24, 27, 0.6)', border: '1px solid #27272a', borderRadius: 999, color: '#e4e4e7', fontSize: 13, fontWeight: 600 }}>React</div>
        <div style={{ padding: '6px 16px', backgroundColor: 'rgba(24, 24, 27, 0.6)', border: '1px solid #27272a', borderRadius: 999, color: '#e4e4e7', fontSize: 13, fontWeight: 600 }}>TypeScript</div>
        <div style={{ padding: '6px 16px', backgroundColor: 'rgba(24, 24, 27, 0.6)', border: '1px solid #27272a', borderRadius: 999, color: '#e4e4e7', fontSize: 13, fontWeight: 600 }}>Next.js</div>
      </div>
    </div>
  </div>

  {/* Stats Cards */}
  <div style={{ display: 'flex', gap: 24, width: '100%', marginBottom: 48, zIndex: 10 }}>
    <div style={{ flex: 1, display: 'flex', flexDirection: 'column', padding: '24px 32px', backgroundColor: 'rgba(24, 24, 27, 0.4)', border: '1px solid #27272a', borderRadius: 16, position: 'relative', overflow: 'hidden' }}>
      <div style={{ position: 'absolute', top: 0, left: 0, width: '100%', height: '100%', backgroundImage: 'radial-gradient(circle, rgba(168, 85, 247, 0.08) 0%, rgba(0,0,0,0) 70%)' }} />
      <div style={{ color: 'white', fontSize: 32, fontWeight: 800 }}>141</div>
      <div style={{ color: '#71717a', fontSize: 11, letterSpacing: 2, fontWeight: 700, marginTop: 6 }}>REPOSITORIES</div>
    </div>
    <div style={{ flex: 1, display: 'flex', flexDirection: 'column', padding: '24px 32px', backgroundColor: 'rgba(24, 24, 27, 0.4)', border: '1px solid #27272a', borderRadius: 16, position: 'relative', overflow: 'hidden' }}>
      <div style={{ position: 'absolute', top: 0, left: 0, width: '100%', height: '100%', backgroundImage: 'radial-gradient(circle, rgba(45, 212, 191, 0.08) 0%, rgba(0,0,0,0) 70%)' }} />
      <div style={{ color: 'white', fontSize: 32, fontWeight: 800 }}>20+</div>
      <div style={{ color: '#71717a', fontSize: 11, letterSpacing: 2, fontWeight: 700, marginTop: 6 }}>PROJECTS</div>
    </div>
    <div style={{ flex: 1, display: 'flex', flexDirection: 'column', padding: '24px 32px', backgroundColor: 'rgba(24, 24, 27, 0.4)', border: '1px solid #27272a', borderRadius: 16, position: 'relative', overflow: 'hidden' }}>
      <div style={{ position: 'absolute', top: 0, left: 0, width: '100%', height: '100%', backgroundImage: 'radial-gradient(circle, rgba(59, 130, 246, 0.08) 0%, rgba(0,0,0,0) 70%)' }} />
      <div style={{ color: 'white', fontSize: 32, fontWeight: 800 }}>500+</div>
      <div style={{ color: '#71717a', fontSize: 11, letterSpacing: 2, fontWeight: 700, marginTop: 6 }}>CONTRIBUTIONS</div>
    </div>
  </div>

  {/* Tech Stack Arsenal */}
  <div style={{ display: 'flex', flexDirection: 'column', width: '100%', backgroundColor: 'rgba(24, 24, 27, 0.4)', border: '1px solid #27272a', borderRadius: 16, padding: '32px 36px', zIndex: 10 }}>
    <div style={{ color: '#52525b', fontSize: 12, fontWeight: 700, letterSpacing: 2, marginBottom: 28 }}>TECH STACK</div>
    
    <div style={{ display: 'flex', alignItems: 'center', marginBottom: 20 }}>
      <div style={{ color: '#a1a1aa', fontSize: 13, fontWeight: 600, width: 140 }}>AI / ML</div>
      <div style={{ display: 'flex', gap: 10, flexWrap: 'wrap', flex: 1 }}>
        <div style={{ padding: '6px 12px', backgroundColor: 'rgba(255,255,255,0.03)', border: '1px solid #27272a', borderRadius: 8, color: '#e4e4e7', fontSize: 13 }}>Python</div>
        <div style={{ padding: '6px 12px', backgroundColor: 'rgba(255,255,255,0.03)', border: '1px solid #27272a', borderRadius: 8, color: '#e4e4e7', fontSize: 13 }}>PyTorch</div>
        <div style={{ padding: '6px 12px', backgroundColor: 'rgba(255,255,255,0.03)', border: '1px solid #27272a', borderRadius: 8, color: '#e4e4e7', fontSize: 13 }}>TensorFlow</div>
        <div style={{ padding: '6px 12px', backgroundColor: 'rgba(255,255,255,0.03)', border: '1px solid #27272a', borderRadius: 8, color: '#e4e4e7', fontSize: 13 }}>LangChain</div>
        <div style={{ padding: '6px 12px', backgroundColor: 'rgba(255,255,255,0.03)', border: '1px solid #27272a', borderRadius: 8, color: '#e4e4e7', fontSize: 13 }}>OpenAI</div>
        <div style={{ padding: '6px 12px', backgroundColor: 'rgba(255,255,255,0.03)', border: '1px solid #27272a', borderRadius: 8, color: '#e4e4e7', fontSize: 13 }}>Ollama</div>
      </div>
    </div>
    
    <div style={{ display: 'flex', alignItems: 'center', marginBottom: 20 }}>
      <div style={{ color: '#a1a1aa', fontSize: 13, fontWeight: 600, width: 140 }}>BACKEND</div>
      <div style={{ display: 'flex', gap: 10, flexWrap: 'wrap', flex: 1 }}>
        <div style={{ padding: '6px 12px', backgroundColor: 'rgba(255,255,255,0.03)', border: '1px solid #27272a', borderRadius: 8, color: '#e4e4e7', fontSize: 13 }}>Node.js</div>
        <div style={{ padding: '6px 12px', backgroundColor: 'rgba(255,255,255,0.03)', border: '1px solid #27272a', borderRadius: 8, color: '#e4e4e7', fontSize: 13 }}>Express</div>
        <div style={{ padding: '6px 12px', backgroundColor: 'rgba(255,255,255,0.03)', border: '1px solid #27272a', borderRadius: 8, color: '#e4e4e7', fontSize: 13 }}>FastAPI</div>
        <div style={{ padding: '6px 12px', backgroundColor: 'rgba(255,255,255,0.03)', border: '1px solid #27272a', borderRadius: 8, color: '#e4e4e7', fontSize: 13 }}>Django</div>
        <div style={{ padding: '6px 12px', backgroundColor: 'rgba(255,255,255,0.03)', border: '1px solid #27272a', borderRadius: 8, color: '#e4e4e7', fontSize: 13 }}>PostgreSQL</div>
        <div style={{ padding: '6px 12px', backgroundColor: 'rgba(255,255,255,0.03)', border: '1px solid #27272a', borderRadius: 8, color: '#e4e4e7', fontSize: 13 }}>MongoDB</div>
        <div style={{ padding: '6px 12px', backgroundColor: 'rgba(255,255,255,0.03)', border: '1px solid #27272a', borderRadius: 8, color: '#e4e4e7', fontSize: 13 }}>Redis</div>
      </div>
    </div>
    
    <div style={{ display: 'flex', alignItems: 'center', marginBottom: 20 }}>
      <div style={{ color: '#a1a1aa', fontSize: 13, fontWeight: 600, width: 140 }}>FRONTEND</div>
      <div style={{ display: 'flex', gap: 10, flexWrap: 'wrap', flex: 1 }}>
        <div style={{ padding: '6px 12px', backgroundColor: 'rgba(255,255,255,0.03)', border: '1px solid #27272a', borderRadius: 8, color: '#e4e4e7', fontSize: 13 }}>React</div>
        <div style={{ padding: '6px 12px', backgroundColor: 'rgba(255,255,255,0.03)', border: '1px solid #27272a', borderRadius: 8, color: '#e4e4e7', fontSize: 13 }}>Next.js</div>
        <div style={{ padding: '6px 12px', backgroundColor: 'rgba(255,255,255,0.03)', border: '1px solid #27272a', borderRadius: 8, color: '#e4e4e7', fontSize: 13 }}>TypeScript</div>
        <div style={{ padding: '6px 12px', backgroundColor: 'rgba(255,255,255,0.03)', border: '1px solid #27272a', borderRadius: 8, color: '#e4e4e7', fontSize: 13 }}>Tailwind CSS</div>
        <div style={{ padding: '6px 12px', backgroundColor: 'rgba(255,255,255,0.03)', border: '1px solid #27272a', borderRadius: 8, color: '#e4e4e7', fontSize: 13 }}>Framer Motion</div>
      </div>
    </div>
    
    <div style={{ display: 'flex', alignItems: 'center' }}>
      <div style={{ color: '#a1a1aa', fontSize: 13, fontWeight: 600, width: 140 }}>CLOUD & DEVOPS</div>
      <div style={{ display: 'flex', gap: 10, flexWrap: 'wrap', flex: 1 }}>
        <div style={{ padding: '6px 12px', backgroundColor: 'rgba(255,255,255,0.03)', border: '1px solid #27272a', borderRadius: 8, color: '#e4e4e7', fontSize: 13 }}>AWS</div>
        <div style={{ padding: '6px 12px', backgroundColor: 'rgba(255,255,255,0.03)', border: '1px solid #27272a', borderRadius: 8, color: '#e4e4e7', fontSize: 13 }}>Azure</div>
        <div style={{ padding: '6px 12px', backgroundColor: 'rgba(255,255,255,0.03)', border: '1px solid #27272a', borderRadius: 8, color: '#e4e4e7', fontSize: 13 }}>Docker</div>
        <div style={{ padding: '6px 12px', backgroundColor: 'rgba(255,255,255,0.03)', border: '1px solid #27272a', borderRadius: 8, color: '#e4e4e7', fontSize: 13 }}>Kubernetes</div>
      </div>
    </div>
  </div>

</div>
```

<br>

```aura width=120 height=44 link="https://www.linkedin.com/in/nitin-k-mishra-520615331" inline align=center
<div style={{ display: 'flex', alignItems: 'center', justifyContent: 'center', width: '100%', height: '100%', backgroundColor: '#0a66c2', borderRadius: 100, border: '1px solid #27272a', fontFamily: 'Inter, sans-serif' }}>
  <div style={{ color: 'white', fontSize: 14, fontWeight: 600 }}>LinkedIn</div>
</div>
```
```aura width=120 height=44 link="https://instagram.com/nitinn10_" inline align=center
<div style={{ display: 'flex', alignItems: 'center', justifyContent: 'center', width: '100%', height: '100%', backgroundColor: '#e1306c', borderRadius: 100, border: '1px solid #27272a', fontFamily: 'Inter, sans-serif' }}>
  <div style={{ color: 'white', fontSize: 14, fontWeight: 600 }}>Instagram</div>
</div>
```
```aura width=120 height=44 link="https://nitinn.dev" inline align=center
<div style={{ display: 'flex', alignItems: 'center', justifyContent: 'center', width: '100%', height: '100%', backgroundColor: '#18181b', borderRadius: 100, border: '1px solid #27272a', fontFamily: 'Inter, sans-serif' }}>
  <div style={{ color: 'white', fontSize: 14, fontWeight: 600 }}>Portfolio</div>
</div>
```
```aura width=240 height=44 link="mailto:nitiniszod10@gmail.com" inline align=center
<div style={{ display: 'flex', alignItems: 'center', justifyContent: 'center', width: '100%', height: '100%', backgroundColor: '#ea4335', borderRadius: 100, border: '1px solid #27272a', fontFamily: 'Inter, sans-serif' }}>
  <div style={{ color: 'white', fontSize: 14, fontWeight: 600 }}>nitiniszod10@gmail.com</div>
</div>
```
</div>
