<svg width="1000" height="700" viewBox="0 0 1000 700" xmlns="http://www.w3.org/2000/svg">
  <!-- Background -->
  <rect width="1000" height="700" fill="#f8fafc"/>
  
  <!-- Title -->
  <text x="500" y="30" text-anchor="middle" font-size="24" font-weight="bold" fill="#1e293b">RentEzy - Microservices Architecture</text>
  
  <!-- Client Layer -->
  <rect x="50" y="60" width="120" height="60" rx="8" fill="#3b82f6" stroke="#1e40af" stroke-width="2"/>
  <text x="110" y="85" text-anchor="middle" font-size="12" font-weight="bold" fill="white">React Frontend</text>
  <text x="110" y="100" text-anchor="middle" font-size="10" fill="white">Web Client</text>
  
  <rect x="50" y="140" width="120" height="60" rx="8" fill="#3b82f6" stroke="#1e40af" stroke-width="2"/>
  <text x="110" y="165" text-anchor="middle" font-size="12" font-weight="bold" fill="white">Mobile App</text>
  <text x="110" y="180" text-anchor="middle" font-size="10" fill="white">Future Client</text>
  
  <!-- API Gateway -->
  <rect x="250" y="100" width="140" height="80" rx="8" fill="#10b981" stroke="#047857" stroke-width="2"/>
  <text x="320" y="125" text-anchor="middle" font-size="14" font-weight="bold" fill="white">API Gateway</text>
  <text x="320" y="145" text-anchor="middle" font-size="10" fill="white">Authentication</text>
  <text x="320" y="160" text-anchor="middle" font-size="10" fill="white">Rate Limiting</text>
  <text x="320" y="175" text-anchor="middle" font-size="10" fill="white">Routing</text>
  
  <!-- Authentication Service -->
  <rect x="450" y="60" width="120" height="60" rx="8" fill="#f59e0b" stroke="#d97706" stroke-width="2"/>
  <text x="510" y="85" text-anchor="middle" font-size="12" font-weight="bold" fill="white">Auth Service</text>
  <text x="510" y="100" text-anchor="middle" font-size="10" fill="white">JWT & OAuth</text>
  
  <!-- Core Business Services -->
  <rect x="450" y="140" width="120" height="60" rx="8" fill="#8b5cf6" stroke="#7c3aed" stroke-width="2"/>
  <text x="510" y="165" text-anchor="middle" font-size="12" font-weight="bold" fill="white">Property Service</text>
  <text x="510" y="180" text-anchor="middle" font-size="10" fill="white">CRUD Operations</text>
  
  <rect x="450" y="220" width="120" height="60" rx="8" fill="#8b5cf6" stroke="#7c3aed" stroke-width="2"/>
  <text x="510" y="245" text-anchor="middle" font-size="12" font-weight="bold" fill="white">Booking Service</text>
  <text x="510" y="260" text-anchor="middle" font-size="10" fill="white">Concurrency Safe</text>
  
  <rect x="450" y="300" width="120" height="60" rx="8" fill="#8b5cf6" stroke="#7c3aed" stroke-width="2"/>
  <text x="510" y="325" text-anchor="middle" font-size="12" font-weight="bold" fill="white">Rent Service</text>
  <text x="510" y="340" text-anchor="middle" font-size="10" fill="white">Payment Logic</text>
  
  <!-- Communication Services -->
  <rect x="600" y="140" width="120" height="60" rx="8" fill="#ec4899" stroke="#db2777" stroke-width="2"/>
  <text x="660" y="165" text-anchor="middle" font-size="12" font-weight="bold" fill="white">Chat Service</text>
  <text x="660" y="180" text-anchor="middle" font-size="10" fill="white">WebSocket</text>
  
  <rect x="600" y="220" width="120" height="60" rx="8" fill="#ec4899" stroke="#db2777" stroke-width="2"/>
  <text x="660" y="245" text-anchor="middle" font-size="12" font-weight="bold" fill="white">Notification</text>
  <text x="660" y="260" text-anchor="middle" font-size="10" fill="white">Real-time Events</text>
  
  <!-- Search Service -->
  <rect x="750" y="140" width="120" height="60" rx="8" fill="#06b6d4" stroke="#0891b2" stroke-width="2"/>
  <text x="810" y="165" text-anchor="middle" font-size="12" font-weight="bold" fill="white">Search Service</text>
  <text x="810" y="180" text-anchor="middle" font-size="10" fill="white">Elasticsearch</text>
  
  <!-- Message Queue -->
  <rect x="450" y="400" width="270" height="60" rx="8" fill="#ef4444" stroke="#dc2626" stroke-width="2"/>
  <text x="585" y="425" text-anchor="middle" font-size="14" font-weight="bold" fill="white">Apache Kafka</text>
  <text x="585" y="445" text-anchor="middle" font-size="11" fill="white">Event Streaming & Async Communication</text>
  
  <!-- Background Processing -->
  <rect x="250" y="400" width="140" height="60" rx="8" fill="#7c3aed" stroke="#6d28d9" stroke-width="2"/>
  <text x="320" y="425" text-anchor="middle" font-size="12" font-weight="bold" fill="white">Celery Workers</text>
  <text x="320" y="445" text-anchor="middle" font-size="10" fill="white">Background Tasks</text>
  
  <!-- Cache -->
  <rect x="750" y="400" width="120" height="60" rx="8" fill="#f97316" stroke="#ea580c" stroke-width="2"/>
  <text x="810" y="425" text-anchor="middle" font-size="12" font-weight="bold" fill="white">Redis Cache</text>
  <text x="810" y="445" text-anchor="middle" font-size="10" fill="white">Session & Cache</text>
  
  <!-- Databases -->
  <rect x="200" y="520" width="120" height="60" rx="8" fill="#374151" stroke="#1f2937" stroke-width="2"/>
  <text x="260" y="545" text-anchor="middle" font-size="12" font-weight="bold" fill="white">PostgreSQL</text>
  <text x="260" y="560" text-anchor="middle" font-size="10" fill="white">Main Database</text>
  
  <rect x="350" y="520" width="120" height="60" rx="8" fill="#374151" stroke="#1f2937" stroke-width="2"/>
  <text x="410" y="545" text-anchor="middle" font-size="12" font-weight="bold" fill="white">Property DB</text>
  <text x="410" y="560" text-anchor="middle" font-size="10" fill="white">PostgreSQL</text>
  
  <rect x="500" y="520" width="120" height="60" rx="8" fill="#374151" stroke="#1f2937" stroke-width="2"/>
  <text x="560" y="545" text-anchor="middle" font-size="12" font-weight="bold" fill="white">Booking DB</text>
  <text x="560" y="560" text-anchor="middle" font-size="10" fill="white">PostgreSQL</text>
  
  <rect x="650" y="520" width="120" height="60" rx="8" fill="#374151" stroke="#1f2937" stroke-width="2"/>
  <text x="710" y="545" text-anchor="middle" font-size="12" font-weight="bold" fill="white">Elasticsearch</text>
  <text x="710" y="560" text-anchor="middle" font-size="10" fill="white">Search Index</text>
  
  <!-- External Services -->
  <rect x="50" y="400" width="120" height="60" rx="8" fill="#059669" stroke="#047857" stroke-width="2"/>
  <text x="110" y="425" text-anchor="middle" font-size="12" font-weight="bold" fill="white">Stripe API</text>
  <text x="110" y="445" text-anchor="middle" font-size="10" fill="white">Payments</text>
  
  <!-- Infrastructure -->
  <rect x="50" y="620" width="800" height="40" rx="8" fill="#1f2937" stroke="#374151" stroke-width="2"/>
  <text x="450" y="640" text-anchor="middle" font-size="14" font-weight="bold" fill="white">AWS EKS (Kubernetes) + Docker Containers + EFS Storage</text>
  
  <!-- Connection Lines -->
  <!-- Client to API Gateway -->
  <line x1="170" y1="90" x2="250" y2="140" stroke="#64748b" stroke-width="2" marker-end="url(#arrowhead)"/>
  <line x1="170" y1="170" x2="250" y2="140" stroke="#64748b" stroke-width="2" marker-end="url(#arrowhead)"/>
  
  <!-- API Gateway to Services -->
  <line x1="390" y1="120" x2="450" y2="90" stroke="#64748b" stroke-width="2" marker-end="url(#arrowhead)"/>
  <line x1="390" y1="140" x2="450" y2="170" stroke="#64748b" stroke-width="2" marker-end="url(#arrowhead)"/>
  <line x1="390" y1="160" x2="450" y2="250" stroke="#64748b" stroke-width="2" marker-end="url(#arrowhead)"/>
  <line x1="390" y1="140" x2="600" y2="170" stroke="#64748b" stroke-width="2" marker-end="url(#arrowhead)"/>
  <line x1="390" y1="160" x2="750" y2="170" stroke="#64748b" stroke-width="2" marker-end="url(#arrowhead)"/>
  
  <!-- Services to Kafka -->
  <line x1="510" y1="200" x2="550" y2="400" stroke="#64748b" stroke-width="2" marker-end="url(#arrowhead)"/>
  <line x1="510" y1="280" x2="570" y2="400" stroke="#64748b" stroke-width="2" marker-end="url(#arrowhead)"/>
  <line x1="660" y1="280" x2="620" y2="400" stroke="#64748b" stroke-width="2" marker-end="url(#arrowhead)"/>
  
  <!-- Services to Databases -->
  <line x1="510" y1="200" x2="410" y2="520" stroke="#64748b" stroke-width="2" marker-end="url(#arrowhead)"/>
  <line x1="510" y1="280" x2="560" y2="520" stroke="#64748b" stroke-width="2" marker-end="url(#arrowhead)"/>
  <line x1="810" y1="200" x2="710" y2="520" stroke="#64748b" stroke-width="2" marker-end="url(#arrowhead)"/>
  
  <!-- External connections -->
  <line x1="250" y1="430" x2="170" y2="430" stroke="#64748b" stroke-width="2" marker-end="url(#arrowhead)"/>
  <line x1="750" y1="430" x2="810" y2="430" stroke="#64748b" stroke-width="2" marker-end="url(#arrowhead)"/>
  
  <!-- Arrow marker definition -->
  <defs>
    <marker id="arrowhead" markerWidth="10" markerHeight="7" refX="10" refY="3.5" orient="auto">
      <polygon points="0 0, 10 3.5, 0 7" fill="#64748b"/>
    </marker>
  </defs>
  
  <!-- Legend -->
  <text x="50" y="680" font-size="12" font-weight="bold" fill="#1e293b">🔄 Event-Driven Architecture | 🔒 JWT Authentication | 📊 Real-time Analytics | 🚀 Auto-scaling on Kubernetes</text>
</svg>
