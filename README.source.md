# README.source.md

This is the editable source plan for the advanced profile system.

The current `README.md` works directly on GitHub using local SVG/PNG assets.
Use this file if you later decide to convert sections into generated readme-aura components.

## Hero

```aura width=1100 height=360
<div style={{
  width: '100%',
  height: '100%',
  background: '#05070A',
  color: '#EAF2FF',
  fontFamily: 'Inter',
  display: 'flex',
  flexDirection: 'column',
  justifyContent: 'center',
  paddingLeft: 64,
  borderRadius: 24,
  border: '1px solid rgba(148,163,184,0.2)'
}}>
  <div style={{ fontSize: 52, fontWeight: 900, letterSpacing: '-2px' }}>
    Building End-to-End AI Systems
  </div>
  <div style={{ fontSize: 26, marginTop: 14, color: '#A7B6D6' }}>
    Voice Agents · RAG · Transformers · Full-Stack Apps
  </div>
  <div style={{ fontSize: 18, marginTop: 34, color: '#8FA3C7' }}>
    GitHub: Rishy-09 · Kaggle: namanchanana · AI/ML + Full-Stack Engineer
  </div>
</div>
```

## Suggested readme-aura workflow

1. Install/init readme-aura in your profile repository.
2. Move advanced JSX-like components into this file.
3. Build generated assets into `.github/assets/`.
4. Keep `README.md` as the final rendered file.
