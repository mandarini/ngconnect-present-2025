---
theme: seriph
background: https://images.unsplash.com/photo-1518709268805-4e9042af2176?ixlib=rb-4.0.3&auto=format&fit=crop&w=2426&q=80
class: 'text-center'
highlighter: shiki
lineNumbers: false
info: |
  ## Cookie Catcher - Angular Connect 2025
  What happens when Angular meets Supabase? Multiplayer mayhem — in the best way.
drawings:
  persist: false
css: unocss
wakeLock: "build"
---

# What happens when Angular meets Supabase?

## Multiplayer mayhem — in the best way.

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Cookie Catcher - Angular Connect 2025 <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 text-xl">
  <carbon-logo-angular class="text-red-500" />
  <span class="mx-2">+</span>
  <logos-supabase-icon />
</div>

---
layout: center
class: text-center
---

# About Me

<div class="grid grid-cols-2 gap-12 items-center">
<div>

# Katerina Skroumpelou

- Software Engineer at **Supabase**
- Loves cats and chocolate 🐱🍫
- Loves to be on stage
- **GDE** for Angular & Maps

</div>
<div>
<img src="https://images.unsplash.com/photo-1494790108755-2616c0763408?ixlib=rb-4.0.3&auto=format&fit=crop&w=500&q=80" class="rounded-full w-64 mx-auto shadow-lg">
</div>
</div>

---
layout: center
class: text-center
---

# What is Supabase?

## The Open Source Firebase Alternative

<div class="grid grid-cols-3 gap-8 mt-12">

<div class="bg-blue-50 p-6 rounded-lg">
<div class="text-4xl mb-4">🐘</div>
<h3 class="text-blue-600 font-bold">PostgreSQL Database</h3>
<p class="text-sm text-gray-600 mt-2">Full SQL database, not NoSQL</p>
</div>

<div class="bg-green-50 p-6 rounded-lg">
<div class="text-4xl mb-4">🚀</div>
<h3 class="text-green-600 font-bold">Auto-generated APIs</h3>
<p class="text-sm text-gray-600 mt-2">REST & GraphQL from your schema</p>
</div>

<div class="bg-purple-50 p-6 rounded-lg">
<div class="text-4xl mb-4">🛠️</div>
<h3 class="text-purple-600 font-bold">Built for developers</h3>
<p class="text-sm text-gray-600 mt-2">Type-safe, modern tooling</p>
</div>

</div>

---
layout: center
class: text-center
---

# Supabase Core Services

## Everything You Need in One Platform

<div class="grid grid-cols-3 gap-8 mt-12">

<div class="bg-blue-50 p-6 rounded-lg">
<div class="text-4xl mb-4">🗄️</div>
<h3 class="text-blue-600 font-bold">Database</h3>
<p class="text-sm text-gray-600 mt-2">PostgreSQL + Vector embeddings</p>
</div>

<div class="bg-green-50 p-6 rounded-lg">
<div class="text-4xl mb-4">🔐</div>
<h3 class="text-green-600 font-bold">Auth</h3>
<p class="text-sm text-gray-600 mt-2">Social, email, phone, magic links</p>
</div>

<div class="bg-purple-50 p-6 rounded-lg">
<div class="text-4xl mb-4">📁</div>
<h3 class="text-purple-600 font-bold">Storage</h3>
<p class="text-sm text-gray-600 mt-2">File storage + CDN + image transforms</p>
</div>

</div>

---
layout: center
class: text-center
---

# Supabase Realtime & Edge

## What Makes It Special

<div class="grid grid-cols-3 gap-8 mt-12">

<div class="bg-yellow-50 p-6 rounded-lg">
<div class="text-4xl mb-4">⚡</div>
<h3 class="text-yellow-600 font-bold">Realtime</h3>
<p class="text-sm text-gray-600 mt-2">Database changes, Broadcast, Presence</p>
</div>

<div class="bg-blue-50 p-6 rounded-lg">
<div class="text-4xl mb-4">🌍</div>
<h3 class="text-blue-600 font-bold">Edge Functions</h3>
<p class="text-sm text-gray-600 mt-2">Global TypeScript functions</p>
</div>

<div class="bg-red-50 p-6 rounded-lg">
<div class="text-4xl mb-4">🔒</div>
<h3 class="text-red-600 font-bold">Security</h3>
<p class="text-sm text-gray-600 mt-2">Row Level Security built-in</p>
</div>

</div>

---
layout: center
class: text-center
---

# Let's Play Together!

## 🍪 Cookie Catcher Game

<div class="text-6xl mb-8">🎮</div>

**https://ngdemo-sb.netlify.app**

<div class="bg-gray-800 text-white p-6 rounded-lg mt-8">

**Rules:**
- Catch cookies 🍪 = **1 point**
- Catch cats 🐱 = **3 points**
- Compete on **live leaderboard!**

</div>

---
layout: center
class: text-center
---

# Building Real-time Multiplayer is Hard

<div class="grid grid-cols-3 gap-8 mt-12">

<div class="bg-red-50 p-6 rounded-lg border-l-4 border-red-400">
<h3 class="text-red-600 font-bold mb-4">Race conditions</h3>
<div class="text-4xl mb-4">⚡</div>
</div>

<div class="bg-orange-50 p-6 rounded-lg border-l-4 border-orange-400">
<h3 class="text-orange-600 font-bold mb-4">State synchronization</h3>
<div class="text-4xl mb-4">🔄</div>
</div>

<div class="bg-yellow-50 p-6 rounded-lg border-l-4 border-yellow-400">
<h3 class="text-yellow-600 font-bold mb-4">Connection management</h3>
<div class="text-4xl mb-4">🔌</div>
</div>

</div>

---
layout: center
class: text-center
---

# The Solution

## Angular Signals + Supabase Realtime

<div class="grid grid-cols-3 gap-8 mt-12">

<div class="bg-blue-50 p-6 rounded-lg">
<div class="text-4xl mb-4">⚡</div>
<h3 class="text-blue-600 font-bold">Reactive state management</h3>
</div>

<div class="bg-green-50 p-6 rounded-lg">
<div class="text-4xl mb-4">🚀</div>
<h3 class="text-green-600 font-bold">Real-time infrastructure</h3>
</div>

<div class="bg-purple-50 p-6 rounded-lg">
<div class="text-4xl mb-4">🛡️</div>
<h3 class="text-purple-600 font-bold">Type-safe development</h3>
</div>

</div>

---
layout: two-cols
---

# Live Data Subscriptions

```typescript
// Subscribe to real-time changes
this.supabase
  .from('game_sessions')
  .on('*', (payload) => {
    // Update Angular signals
    this.gameState.set(payload.new);
  })
  .subscribe();
```

::right::

<div class="pl-8">

## Real-time Database Changes

- **PostgreSQL** change streams
- **WebSocket** delivery  
- **Automatic** UI updates

<div class="mt-8 text-center">
<div class="text-6xl">📊</div>
<p class="text-gray-600 mt-4">Live data, zero effort</p>
</div>

</div>

---
layout: center
class: text-center
---

# Who's Online Right Now

## Presence Tracking

<div class="grid grid-cols-3 gap-8 mt-12">

<div class="bg-green-50 p-6 rounded-lg">
<div class="text-4xl mb-4">👥</div>
<h3 class="text-green-600 font-bold">Real-time user count</h3>
</div>

<div class="bg-blue-50 p-6 rounded-lg">
<div class="text-4xl mb-4">📢</div>
<h3 class="text-blue-600 font-bold">Join/leave notifications</h3>
</div>

<div class="bg-purple-50 p-6 rounded-lg">
<div class="text-4xl mb-4">🧹</div>
<h3 class="text-purple-600 font-bold">Automatic cleanup on disconnect</h3>
</div>

</div>

---
layout: two-cols
---

# See Everyone's Interactions

```typescript
// Track cursor position
@HostListener('mousemove', ['$event'])
onMouseMove(event: MouseEvent) {
  throttle(() => {
    this.presence.track({
      x: event.clientX,
      y: event.clientY,
      user: this.userId
    });
  }, 50);
}
```

::right::

<div class="pl-8">

## Live Cursor Tracking

- **Desktop:** Mouse cursors
- **Mobile:** Touch ripples
- **50ms** update throttling

<div class="mt-8 text-center">
<div class="text-6xl">👆</div>
<p class="text-gray-600 mt-4">Every move is shared</p>
</div>

</div>

---
layout: center
class: text-center
---

# Solving Race Conditions

## Atomic Operations

<div class="grid grid-cols-3 gap-8 mt-12">

<div class="bg-red-50 p-6 rounded-lg">
<div class="text-4xl mb-4">🔐</div>
<h3 class="text-red-600 font-bold">Edge Functions for security</h3>
</div>

<div class="bg-blue-50 p-6 rounded-lg">
<div class="text-4xl mb-4">💎</div>
<h3 class="text-blue-600 font-bold">Database-level atomicity</h3>
</div>

<div class="bg-green-50 p-6 rounded-lg">
<div class="text-4xl mb-4">🏆</div>
<h3 class="text-green-600 font-bold">First-tap-wins logic</h3>
</div>

</div>

---
layout: center
class: text-center
---

# 60fps with 250,000+ Users

## Performance at Scale

<div class="grid grid-cols-3 gap-8 mt-12">

<div class="bg-orange-50 p-6 rounded-lg">
<div class="text-4xl mb-4">🎯</div>
<h3 class="text-orange-600 font-bold">OnPush change detection</h3>
</div>

<div class="bg-blue-50 p-6 rounded-lg">
<div class="text-4xl mb-4">⚡</div>
<h3 class="text-blue-600 font-bold">Computed signals</h3>
</div>

<div class="bg-green-50 p-6 rounded-lg">
<div class="text-4xl mb-4">🚀</div>
<h3 class="text-green-600 font-bold">Optimistic UI updates</h3>
</div>

</div>

---
layout: two-cols
---

# Row Level Security Made Simple

```sql
-- Enable RLS on tables
ALTER TABLE game_sessions 
ENABLE ROW LEVEL SECURITY;

-- Create policies
CREATE POLICY "Users can read own sessions"
  ON game_sessions FOR SELECT
  USING (user_id = auth.uid());
```

::right::

<div class="pl-8">

## Database Security

- **Enable** RLS policies
- **Realtime** subscriptions
- **Protected** Edge Functions

<div class="mt-8 text-center">
<div class="text-6xl">🔒</div>
<p class="text-gray-600 mt-4">Security by default</p>
</div>

</div>

---
layout: center
class: text-center
---

# Mobile-First Design

## Cross-Platform Magic

<div class="grid grid-cols-3 gap-8 mt-12">

<div class="bg-blue-50 p-6 rounded-lg">
<div class="text-4xl mb-4">📱</div>
<h3 class="text-blue-600 font-bold">Device detection</h3>
</div>

<div class="bg-green-50 p-6 rounded-lg">
<div class="text-4xl mb-4">🎮</div>
<h3 class="text-green-600 font-bold">Adaptive interactions</h3>
</div>

<div class="bg-purple-50 p-6 rounded-lg">
<div class="text-4xl mb-4">🌍</div>
<h3 class="text-purple-600 font-bold">Unified multiplayer experience</h3>
</div>

</div>

---
layout: two-cols
---

# Type-Safe Real-time Development

```typescript
// Generated types from database schema
interface GameSession {
  id: string;
  user_id: string;
  score: number;
  created_at: string;
}

const { data } = await supabase
  .from('game_sessions')
  .select<'*', GameSession>('*');
```

::right::

<div class="pl-8">

## Developer Experience

- **Generated** TypeScript types
- **Full** IDE support
- **End-to-end** type safety

<div class="mt-8 text-center">
<div class="text-6xl">🛠️</div>
<p class="text-gray-600 mt-4">Types all the way down</p>
</div>

</div>

---
layout: center
class: text-center
---

# Simple but Powerful

## Architecture

<div class="grid grid-cols-3 gap-8 mt-12">

<div class="bg-red-50 p-6 rounded-lg">
<div class="text-4xl mb-4">🅰️</div>
<h3 class="text-red-600 font-bold">Angular: Reactive UI</h3>
</div>

<div class="bg-green-50 p-6 rounded-lg">
<div class="text-4xl mb-4">⚡</div>
<h3 class="text-green-600 font-bold">Supabase: Real-time backend</h3>
</div>

<div class="bg-blue-50 p-6 rounded-lg">
<div class="text-4xl mb-4">🔌</div>
<h3 class="text-blue-600 font-bold">One WebSocket connection</h3>
</div>

</div>

---
layout: center
class: text-center
---

# Production-Ready Performance

## Real-World Results

<div class="grid grid-cols-2 gap-8 mt-12">

<div class="bg-green-50 p-6 rounded-lg border-l-4 border-green-400">
<h3 class="text-green-600 font-bold mb-2">✅ 250,000+ concurrent users</h3>
</div>

<div class="bg-blue-50 p-6 rounded-lg border-l-4 border-blue-400">
<h3 class="text-blue-600 font-bold mb-2">✅ Sub-50ms latency</h3>
</div>

<div class="bg-purple-50 p-6 rounded-lg border-l-4 border-purple-400">
<h3 class="text-purple-600 font-bold mb-2">✅ Automatic scaling</h3>
</div>

<div class="bg-orange-50 p-6 rounded-lg border-l-4 border-orange-400">
<h3 class="text-orange-600 font-bold mb-2">✅ Zero infrastructure management</h3>
</div>

</div>

---
layout: center
class: text-center
---

# Why Angular + Supabase Works

## Key Takeaways

<div class="grid grid-cols-3 gap-8 mt-12">

<div class="bg-blue-50 p-8 rounded-lg">
<div class="text-5xl mb-4">⚡</div>
<h3 class="text-blue-600 font-bold">Reactive by default</h3>
</div>

<div class="bg-green-50 p-8 rounded-lg">
<div class="text-5xl mb-4">🛡️</div>
<h3 class="text-green-600 font-bold">Type-safe across the stack</h3>
</div>

<div class="bg-purple-50 p-8 rounded-lg">
<div class="text-5xl mb-4">📈</div>
<h3 class="text-purple-600 font-bold">Scalable out of the box</h3>
</div>

</div>

---
layout: center
class: text-center
---

# Beyond Games

## What You Can Build

<div class="grid grid-cols-2 gap-8 mt-12">

<div class="bg-blue-50 p-6 rounded-lg">
<div class="text-4xl mb-4">💬</div>
<h3 class="text-blue-600 font-bold">Chat applications</h3>
</div>

<div class="bg-green-50 p-6 rounded-lg">
<div class="text-4xl mb-4">📊</div>
<h3 class="text-green-600 font-bold">Collaborative dashboards</h3>
</div>

<div class="bg-yellow-50 p-6 rounded-lg">
<div class="text-4xl mb-4">✏️</div>
<h3 class="text-yellow-600 font-bold">Document editing</h3>
</div>

<div class="bg-purple-50 p-6 rounded-lg">
<div class="text-4xl mb-4">📍</div>
<h3 class="text-purple-600 font-bold">Live tracking</h3>
</div>

</div>

---
layout: center
class: text-center
---

# Thank You!

## Questions?

<div class="text-6xl mb-8">🍪</div>

<div class="text-xl space-y-4">

**🎮 Demo:** https://ngdemo-sb.netlify.app

**📚 Source Code:** https://github.com/mandarini/ac-demo-sb

</div>

<div class="mt-12 text-lg">

**Connect with me:**
- 🐦 [@psybercity](https://x.com/psybercity)
- 🌐 [psyber.city](https://psyber.city)  
- 💼 [github.com/mandarini](https://github.com/mandarini)

</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>