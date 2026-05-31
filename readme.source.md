<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=wave&color=0:6622ee,100:0088ff&height=200&section=header&animation=fadeIn" alt="header" />
</p>

```aura width=860 height=200 link="https://collectioneur.github.io/readme-aura/"
<div style={{
  width: '100%', height: '100%', background: '#08080c',
  display: 'flex', alignItems: 'center', fontFamily: 'Inter',
  position: 'relative', overflow: 'hidden', borderRadius: 16,
  border: '1px solid rgba(110,80,220,0.18)'
}}>

  <style>{`
      @keyframes float-slow {
        0%, 100% { transform: translateX(0px); opacity: 0.8; }
        50% { transform: translateX(350px); opacity: 1.2; }
      }
      @keyframes float-medium {
        0%, 100% { transform: translateX(0px); opacity: 0.7; }
        50% { transform: translateX(-250px); opacity: 1.1; }
      }
      @keyframes float-fast {
        0%, 100% { transform: translateX(0px); opacity: 0.9; }
        50% { transform: translateX(200px); opacity: 0.6; }
      }
      @keyframes float-diagonal {
        0%, 100% { transform: translateX(0px); opacity: 0.75; }
        50% { transform: translateX(300px); opacity: 1.0; }
      }
      @keyframes float-wave {
        0%, 100% { transform: translateX(0px); opacity: 0.65; }
        33% { transform: translateX(-160px); opacity: 0.9; }
        66% { transform: translateX(80px); opacity: 1.0; }
      }
      @keyframes float-pulse {
        0%, 100% { transform: scale(1); opacity: 0.8; }
        50% { transform: scale(1.3); opacity: 0.4; }
      }
      #glow-1 { animation: float-slow 8s ease-in-out infinite; }
      #glow-2 { animation: float-medium 12s ease-in-out infinite; }
      #glow-3 { animation: float-fast 9s ease-in-out infinite; }
      #glow-4 { animation: float-slow 11s ease-in-out infinite reverse; }
      #glow-5 { animation: float-medium 14s ease-in-out infinite reverse; }
      #glow-6 { animation: float-diagonal 10s ease-in-out infinite; }
      #glow-7 { animation: float-wave 13s ease-in-out infinite; }
      #glow-8 { animation: float-pulse 7s ease-in-out infinite; }
    `}</style>

  <svg width="860" height="200" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="g1" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(110,20,210,0.72)" />
        <stop offset="40%" stopColor="rgba(90,15,180,0.35)" />
        <stop offset="70%" stopColor="rgba(90,15,180,0)" />
      </radialGradient>
      <radialGradient id="g2" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(40,60,255,0.6)" />
        <stop offset="45%" stopColor="rgba(30,50,200,0.25)" />
        <stop offset="70%" stopColor="rgba(30,50,200,0)" />
      </radialGradient>
      <radialGradient id="g3" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(0,130,255,0.45)" />
        <stop offset="50%" stopColor="rgba(0,100,220,0.18)" />
        <stop offset="70%" stopColor="rgba(0,100,220,0)" />
      </radialGradient>
      <radialGradient id="g4" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(0,190,230,0.32)" />
        <stop offset="70%" stopColor="rgba(0,190,230,0)" />
      </radialGradient>
      <radialGradient id="g5" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(90,30,200,0.38)" />
        <stop offset="70%" stopColor="rgba(90,30,200,0)" />
      </radialGradient>
      <radialGradient id="g6" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(160,30,255,0.55)" />
        <stop offset="45%" stopColor="rgba(130,20,220,0.22)" />
        <stop offset="70%" stopColor="rgba(130,20,220,0)" />
      </radialGradient>
      <radialGradient id="g7" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(20,60,255,0.42)" />
        <stop offset="50%" stopColor="rgba(10,40,200,0.16)" />
        <stop offset="70%" stopColor="rgba(10,40,200,0)" />
      </radialGradient>
      <radialGradient id="g8" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(0,170,255,0.40)" />
        <stop offset="50%" stopColor="rgba(0,130,220,0.15)" />
        <stop offset="70%" stopColor="rgba(0,130,220,0)" />
      </radialGradient>
    </defs>

    <ellipse id="glow-1" cx="180" cy="230" rx="260" ry="190" fill="url(#g1)" />
    <ellipse id="glow-2" cx="300" cy="240" rx="220" ry="160" fill="url(#g2)" />
    <ellipse id="glow-3" cx="420" cy="240" rx="180" ry="140" fill="url(#g3)" />
    <ellipse id="glow-4" cx="550" cy="250" rx="150" ry="120" fill="url(#g4)" />
    <ellipse id="glow-5" cx="750" cy="250" rx="130" ry="110" fill="url(#g5)" />
    <ellipse id="glow-6" cx="300" cy="240" rx="180" ry="140" fill="url(#g6)" />
    <ellipse id="glow-7" cx="490" cy="230" rx="220" ry="170" fill="url(#g7)" />
    <ellipse id="glow-8" cx="590" cy="250" rx="150" ry="130" fill="url(#g8)" />
  </svg>

  <div style={{
    position: 'absolute', left: 48, top: 52, width: 96, height: 96,
    borderRadius: 48, background: 'linear-gradient(135deg, #6622ee, #0088ff)',
    display: 'flex', alignItems: 'center', justifyContent: 'center',
  }}>
    <img src={github?.user?.avatarUrl ?? 'https://github.com/aki-seven.png'} width={88} height={88} style={{ borderRadius: 44 }} />
  </div>

  <div style={{ display:'flex', flexDirection:'column', marginLeft:168, gap:8, zIndex: 10 }}>
    <div style={{ display:'flex', fontSize:38, fontWeight:800, color:'#ffffff', letterSpacing:'-1px', lineHeight:1 }}>
      {github?.user?.name || github?.user?.login || 'aki-seven'}
    </div>
    <div style={{ display:'flex', fontSize:15, color:'rgba(180,165,255,0.8)', fontWeight:400, letterSpacing:'0.3px' }}>
      {github?.user?.bio || 'Java | Python | VAPT | WAPT | HQX Top 200'}
    </div>
    <div style={{ display:'flex', gap:8, marginTop:6, flexWrap: 'wrap' }}>
      {((github && github.languages && github.languages.length > 0)
        ? github.languages.slice(0, 5).map(function(l) { return l.name; })
        : ['Python', 'TypeScript', 'Java', 'Shell', 'HTML']
      ).map(function(tag, i) {
        return (
          <div key={tag + '-' + i} style={{
            display:'flex', padding:'4px 12px', borderRadius:20,
            background:'rgba(80,40,220,0.18)', border:'1px solid rgba(100,70,240,0.32)',
            color:'rgba(205,195,255,0.85)', fontSize:12, fontWeight:600,
          }}>{tag}</div>
        );
      })}
    </div>
  </div>
</div>
```

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=slice&color=0:6622ee,100:0088ff&height=80&section=header&text=FEATURED%20PROJECTS&fontSize=30&fontColor=ffffff&animation=fadeIn" alt="projects" />
</p>

```aura width=860 height=320 link="https://collectioneur.github.io/readme-aura/"
(function() {
  var projects = [
    {
      name: 'CTF_enum',
      desc: 'Automation script for recon and enumeration in CTF challenges',
      lang: 'Python',
      url: 'https://github.com/aki-seven/CTF_enum',
      color: '#3572A5',
      stars: 1,
    },
    {
      name: 'Hash3r',
      desc: 'CLI tool to hash strings/files with Argon2, Bcrypt, MD5, SHA256, Blake3',
      lang: 'Python',
      url: 'https://github.com/aki-seven/Hash3r',
      color: '#3572A5',
      stars: 0,
    },
    {
      name: 'ytdesktop',
      desc: 'A Desktop App for YouTube built with Electron',
      lang: 'TypeScript',
      url: 'https://github.com/aki-seven/ytdesktop',
      color: '#3178c6',
      stars: 0,
    },
    {
      name: 'Internship-Projects',
      desc: 'All internship projects bundled in a single repository',
      lang: 'Python',
      url: 'https://github.com/aki-seven/Internship-Projects',
      color: '#3572A5',
      stars: 0,
    },
    {
      name: 'DOTFILES',
      desc: 'My configuration files for my setup. Feel free to use em.',
      lang: 'Shell',
      url: 'https://github.com/aki-seven/DOTFILES',
      color: '#89e051',
      stars: 0,
    },
  ];

  return (
    <div style={{
      width: '100%', height: '100%', background: '#08080c',
      display: 'flex', flexDirection: 'column', fontFamily: 'Inter',
      padding: '24px 32px', gap: 16, borderRadius: 16,
      border: '1px solid rgba(110,80,220,0.18)',
      position: 'relative', overflow: 'hidden',
    }}>
      <style>{`
        @keyframes float-slow {
          0%, 100% { transform: translateX(0px); opacity: 0.8; }
          50% { transform: translateX(350px); opacity: 1.2; }
        }
        @keyframes float-medium {
          0%, 100% { transform: translateX(0px); opacity: 0.7; }
          50% { transform: translateX(-250px); opacity: 1.1; }
        }
        @keyframes float-fast {
          0%, 100% { transform: translateX(0px); opacity: 0.9; }
          50% { transform: translateX(200px); opacity: 0.6; }
        }
        #glow-p1 { animation: float-slow 9s ease-in-out infinite; }
        #glow-p2 { animation: float-medium 12s ease-in-out infinite; }
        #glow-p3 { animation: float-fast 8s ease-in-out infinite; }
      `}</style>

      <svg width="860" height="320" style={{ position: 'absolute', top: 0, left: 0 }}>
        <defs>
          <radialGradient id="gp1" cx="50%" cy="50%" r="50%">
            <stop offset="0%" stopColor="rgba(102,34,238,0.4)" />
            <stop offset="70%" stopColor="rgba(102,34,238,0)" />
          </radialGradient>
          <radialGradient id="gp2" cx="50%" cy="50%" r="50%">
            <stop offset="0%" stopColor="rgba(0,136,255,0.3)" />
            <stop offset="70%" stopColor="rgba(0,136,255,0)" />
          </radialGradient>
          <radialGradient id="gp3" cx="50%" cy="50%" r="50%">
            <stop offset="0%" stopColor="rgba(80,40,220,0.35)" />
            <stop offset="70%" stopColor="rgba(80,40,220,0)" />
          </radialGradient>
        </defs>
        <ellipse id="glow-p1" cx="200" cy="300" rx="250" ry="180" fill="url(#gp1)" />
        <ellipse id="glow-p2" cx="500" cy="310" rx="200" ry="150" fill="url(#gp2)" />
        <ellipse id="glow-p3" cx="750" cy="300" rx="180" ry="140" fill="url(#gp3)" />
      </svg>

      <div style={{ display:'flex', flexWrap:'wrap', gap:14, zIndex:10 }}>
        {projects.map(function(p) {
          return (
            <a key={p.name} href={p.url} style={{
              display:'flex', flexDirection:'column', width:'260px',
              padding:'16px', borderRadius:12, textDecoration:'none',
              background:'rgba(20,15,40,0.7)', border:'1px solid rgba(110,80,220,0.2)',
              gap:8,
            }}>
              <div style={{ display:'flex', alignItems:'center', gap:8 }}>
                <div style={{
                  width:10, height:10, borderRadius:5, background:p.color,
                }} />
                <div style={{
                  fontSize:16, fontWeight:700, color:'#ffffff', letterSpacing:'-0.3px',
                }}>{p.name}</div>
              </div>
              <div style={{
                fontSize:12, color:'rgba(180,165,255,0.7)', lineHeight:1.4,
                minHeight:34,
              }}>{p.desc}</div>
              <div style={{ display:'flex', alignItems:'center', gap:8, marginTop:4 }}>
                <div style={{
                  padding:'2px 8px', borderRadius:10,
                  background:p.color + '20', border:'1px solid ' + p.color + '40',
                  color:p.color, fontSize:10, fontWeight:600,
                }}>{p.lang}</div>
                {p.stars > 0 && (
                  <div style={{
                    display:'flex', alignItems:'center', gap:3,
                    color:'rgba(255,215,0,0.8)', fontSize:10, fontWeight:600,
                  }}>
                    <svg width="10" height="10" viewBox="0 0 16 16" fill="currentColor">
                      <path d="M8 .25a.75.75 0 01.673.418l1.882 3.815 4.21.612a.75.75 0 01.416 1.279l-3.046 2.97.719 4.192a.75.75 0 01-1.088.791L8 12.347l-3.766 1.98a.75.75 0 01-1.088-.79l.72-4.194L.818 6.374a.75.75 0 01.416-1.28l4.21-.611L7.327.668A.75.75 0 018 .25z"/>
                    </svg>
                    {p.stars}
                  </div>
                )}
              </div>
            </a>
          );
        })}
      </div>
    </div>
  );
})()
```

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rounded&color=0:08080c,100:1a1a2e&height=60&section=footer&text=powered%20by%20readme-aura&fontSize=14&fontColor=9080dc&animation=fadeIn" alt="footer" />
</p>
