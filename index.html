import React, { useState, useRef, useEffect } from "react";

// ---- Brand: Cantalk (purple / white) ----
const BRAND = "#6C4FD1";
const BRAND_LIGHT = "#8B6FE8";

const THEME = {
  light: {
    bg: "#F8F6F1",
    surface: "#FFFFFF",
    ink: "#24232B",
    muted: "#8F897A",
    border: "#ECE7DB",
    bubbleThem: "#FFFFFF",
    bubbleThemText: "#24232B",
  },
  dark: {
    bg: "#1B1A20",
    surface: "#25242C",
    ink: "#F4F2EC",
    muted: "#9C978C",
    border: "#34333C",
    bubbleThem: "#2E2D37",
    bubbleThemText: "#F4F2EC",
  },
};

const CONTACTS = {
  hamza: {
    id: "hamza",
    name: "Hamza",
    status: "husband \u2764\uFE0F on his way home",
    initial: "H",
    gradient: "linear-gradient(135deg, #4C6FE0 0%, #2C3E8C 100%)",
    online: true,
    time: "2:14 PM",
    unread: 2,
    lastMessage: "Almost there, put the rice on 😄",
    messages: [
      { from: "them", text: "Hey habibi, leaving the office now", time: "1:58 PM" },
      { from: "me", text: "Finally! Traffic looked bad on the map", time: "2:01 PM" },
      { from: "them", text: "Yeah it's slow, give me 20 min", time: "2:02 PM" },
      { from: "me", text: "Okay, I'll start dinner", time: "2:03 PM" },
      { from: "them", text: "You're the best 🥰", time: "2:03 PM" },
      { from: "them", text: "Almost there, put the rice on 😄", time: "2:14 PM" },
    ],
  },
  yoonchae: {
    id: "yoonchae",
    name: "Yoonchae",
    status: "KATSEYE \u2728 practicing choreo",
    initial: "Y",
    gradient: "linear-gradient(135deg, #F49BC1 0%, #B15FC9 100%)",
    online: true,
    time: "11:40 AM",
    unread: 0,
    lastMessage: "See you at the next comeback stage!",
    messages: [
      { from: "them", text: "Hi! Thanks so much for the support 🩷", time: "11:20 AM" },
      { from: "me", text: "You guys did amazing this week!!", time: "11:32 AM" },
      { from: "them", text: "That means a lot, we worked really hard on it", time: "11:36 AM" },
      { from: "them", text: "See you at the next comeback stage!", time: "11:40 AM" },
    ],
  },
};

const ME = {
  name: "Salma",
  status: "🌙 living my best life",
  initial: "S",
  gradient: `linear-gradient(135deg, ${BRAND_LIGHT} 0%, ${BRAND} 100%)`,
};

// ---------- small building blocks ----------

function StatusBar({ t }) {
  return (
    <div
      style={{
        height: 30,
        flexShrink: 0,
        display: "flex",
        alignItems: "center",
        justifyContent: "space-between",
        padding: "0 20px",
        background: t.bg,
        color: t.ink,
        fontSize: 12.5,
        fontWeight: 600,
        fontFamily: "system-ui, sans-serif",
      }}
    >
      <span>9:41</span>
      <span style={{ display: "flex", gap: 4, alignItems: "center" }}>
        <span>􀙇</span>
        <span>▂▄▆</span>
        <span>🔋</span>
      </span>
    </div>
  );
}

function Logo({ size = 26, showWordmark = true, t }) {
  return (
    <div style={{ display: "flex", alignItems: "center", gap: 8 }}>
      <div
        style={{
          width: size,
          height: size,
          borderRadius: size * 0.32,
          background: `linear-gradient(135deg, ${BRAND_LIGHT} 0%, ${BRAND} 100%)`,
          display: "flex",
          alignItems: "center",
          justifyContent: "center",
          flexShrink: 0,
          boxShadow: `0 3px 8px rgba(108,79,209,0.35)`,
        }}
      >
        <svg width={size * 0.56} height={size * 0.56} viewBox="0 0 24 24" fill="none">
          <path
            d="M4 12c0-4.4 3.6-8 8-8s8 3.6 8 8-3.6 8-8 8c-1.1 0-2.1-.2-3-.6L4 21l1.4-4.6C4.5 15 4 13.6 4 12z"
            fill="#FFFFFF"
          />
        </svg>
      </div>
      {showWordmark && (
        <span
          style={{
            fontFamily: "'Baloo 2', system-ui, sans-serif",
            fontWeight: 800,
            fontSize: size * 0.62,
            color: BRAND,
            letterSpacing: 0.2,
          }}
        >
          Cantalk
        </span>
      )}
    </div>
  );
}

function Avatar({ initial, gradient, size = 48, online }) {
  return (
    <div style={{ position: "relative", width: size, height: size, flexShrink: 0 }}>
      <div
        style={{
          width: size,
          height: size,
          borderRadius: "16px",
          background: gradient,
          display: "flex",
          alignItems: "center",
          justifyContent: "center",
          color: "#fff",
          fontFamily: "'Baloo 2', system-ui, sans-serif",
          fontWeight: 700,
          fontSize: size * 0.42,
          boxShadow: "0 2px 6px rgba(0,0,0,0.14)",
        }}
      >
        {initial}
      </div>
      {online && (
        <span
          style={{
            position: "absolute",
            bottom: -2,
            right: -2,
            width: size * 0.28,
            height: size * 0.28,
            borderRadius: "50%",
            background: "#45B26B",
            border: "2.5px solid #FFFFFF",
          }}
        />
      )}
    </div>
  );
}

function TopBar({ title, t, onSettings }) {
  return (
    <div
      style={{
        display: "flex",
        alignItems: "center",
        justifyContent: "space-between",
        padding: "10px 16px 6px",
        background: t.bg,
        flexShrink: 0,
      }}
    >
      <Logo size={26} t={t} />
      <button
        onClick={onSettings}
        style={{
          background: "none",
          border: "none",
          fontSize: 18,
          cursor: "pointer",
          color: t.ink,
          padding: 4,
        }}
        aria-label="Settings"
      >
        ⚙️
      </button>
    </div>
  );
}

function SearchBar({ t, placeholder }) {
  return (
    <div style={{ padding: "6px 16px 10px" }}>
      <div
        style={{
          display: "flex",
          alignItems: "center",
          gap: 8,
          background: t.surface,
          border: `1px solid ${t.border}`,
          borderRadius: 12,
          padding: "8px 12px",
        }}
      >
        <span style={{ fontSize: 13, color: t.muted }}>🔍</span>
        <span style={{ fontSize: 13.5, color: t.muted, fontFamily: "system-ui, sans-serif" }}>
          {placeholder}
        </span>
      </div>
    </div>
  );
}

function SectionLabel({ children, t }) {
  return (
    <div style={{ padding: "10px 20px 6px", fontSize: 12, color: t.muted, fontWeight: 700, letterSpacing: 0.3 }}>
      {children}
    </div>
  );
}

function Toggle({ on, onChange }) {
  return (
    <button
      onClick={() => onChange(!on)}
      style={{
        width: 42,
        height: 24,
        borderRadius: 999,
        border: "none",
        background: on ? BRAND : "#D8D3C6",
        position: "relative",
        cursor: "pointer",
        flexShrink: 0,
        transition: "background 0.15s ease",
      }}
      aria-pressed={on}
    >
      <span
        style={{
          position: "absolute",
          top: 3,
          left: on ? 21 : 3,
          width: 18,
          height: 18,
          borderRadius: "50%",
          background: "#FFFFFF",
          boxShadow: "0 1px 3px rgba(0,0,0,0.25)",
          transition: "left 0.15s ease",
        }}
      />
    </button>
  );
}

function BottomNav({ tab, setTab, t }) {
  const items = [
    { key: "friends", label: "Friends", icon: "👥" },
    { key: "chats", label: "Chats", icon: "💬" },
    { key: "settings", label: "Settings", icon: "⚙️" },
  ];
  return (
    <div
      style={{
        display: "flex",
        borderTop: `1px solid ${t.border}`,
        background: t.surface,
        flexShrink: 0,
      }}
    >
      {items.map((it) => {
        const active = tab === it.key;
        return (
          <button
            key={it.key}
            onClick={() => setTab(it.key)}
            style={{
              flex: 1,
              border: "none",
              background: "none",
              padding: "10px 0 12px",
              display: "flex",
              flexDirection: "column",
              alignItems: "center",
              gap: 3,
              cursor: "pointer",
              color: active ? BRAND : t.muted,
            }}
          >
            <span style={{ fontSize: 18, opacity: active ? 1 : 0.55 }}>{it.icon}</span>
            <span
              style={{
                fontFamily: "system-ui, sans-serif",
                fontSize: 11,
                fontWeight: active ? 700 : 500,
              }}
            >
              {it.label}
            </span>
          </button>
        );
      })}
    </div>
  );
}

// ---------- tabs ----------

function FriendsTab({ onOpenProfile, t }) {
  return (
    <div style={{ flex: 1, overflowY: "auto" }}>
      <SearchBar t={t} placeholder="Search friends" />
      <div
        onClick={() => onOpenProfile("me")}
        style={{
          display: "flex",
          alignItems: "center",
          gap: 12,
          padding: "14px 16px",
          background: t.surface,
          margin: "0 12px 10px",
          borderRadius: 18,
          cursor: "pointer",
        }}
      >
        <Avatar initial={ME.initial} gradient={ME.gradient} size={54} />
        <div>
          <div style={{ fontFamily: "'Baloo 2', system-ui, sans-serif", fontWeight: 700, fontSize: 16, color: t.ink }}>
            {ME.name}
          </div>
          <div style={{ fontSize: 12.5, color: t.muted, marginTop: 2 }}>{ME.status}</div>
        </div>
      </div>

      <SectionLabel t={t}>FRIENDS · {Object.keys(CONTACTS).length}</SectionLabel>

      {Object.values(CONTACTS).map((c) => (
        <div
          key={c.id}
          onClick={() => onOpenProfile(c.id)}
          style={{
            display: "flex",
            alignItems: "center",
            gap: 12,
            padding: "10px 20px",
            cursor: "pointer",
          }}
        >
          <Avatar initial={c.initial} gradient={c.gradient} size={46} online={c.online} />
          <div>
            <div style={{ fontFamily: "system-ui, sans-serif", fontWeight: 600, fontSize: 15, color: t.ink }}>
              {c.name}
            </div>
            <div style={{ fontSize: 12.5, color: t.muted, marginTop: 1 }}>{c.status}</div>
          </div>
        </div>
      ))}
    </div>
  );
}

function ChatsTab({ onOpenChat, t }) {
  return (
    <div style={{ flex: 1, overflowY: "auto", position: "relative" }}>
      <SearchBar t={t} placeholder="Search chats" />
      {Object.values(CONTACTS).map((c) => (
        <div
          key={c.id}
          onClick={() => onOpenChat(c.id)}
          style={{
            display: "flex",
            alignItems: "center",
            gap: 12,
            padding: "12px 20px",
            cursor: "pointer",
          }}
        >
          <Avatar initial={c.initial} gradient={c.gradient} size={50} online={c.online} />
          <div style={{ flex: 1, minWidth: 0 }}>
            <div style={{ display: "flex", justifyContent: "space-between" }}>
              <span style={{ fontFamily: "system-ui, sans-serif", fontWeight: 600, fontSize: 15, color: t.ink }}>
                {c.name}
              </span>
              <span style={{ fontSize: 11.5, color: t.muted }}>{c.time}</span>
            </div>
            <div style={{ display: "flex", justifyContent: "space-between", marginTop: 3 }}>
              <span
                style={{
                  fontSize: 13,
                  color: t.muted,
                  overflow: "hidden",
                  textOverflow: "ellipsis",
                  whiteSpace: "nowrap",
                  maxWidth: 190,
                }}
              >
                {c.lastMessage}
              </span>
              {c.unread > 0 && (
                <span
                  style={{
                    background: BRAND,
                    color: "#FFFFFF",
                    fontSize: 11,
                    fontWeight: 700,
                    borderRadius: "999px",
                    minWidth: 18,
                    height: 18,
                    display: "flex",
                    alignItems: "center",
                    justifyContent: "center",
                    padding: "0 5px",
                  }}
                >
                  {c.unread}
                </span>
              )}
            </div>
          </div>
        </div>
      ))}

      <button
        style={{
          position: "absolute",
          bottom: 16,
          right: 16,
          width: 48,
          height: 48,
          borderRadius: "50%",
          border: "none",
          background: `linear-gradient(135deg, ${BRAND_LIGHT} 0%, ${BRAND} 100%)`,
          color: "#FFFFFF",
          fontSize: 20,
          cursor: "pointer",
          boxShadow: "0 6px 16px rgba(108,79,209,0.4)",
        }}
        aria-label="New chat"
      >
        ✎
      </button>
    </div>
  );
}

function SettingsRow({ icon, label, value, onClick, t, danger }) {
  return (
    <div
      onClick={onClick}
      style={{
        display: "flex",
        alignItems: "center",
        gap: 12,
        padding: "13px 20px",
        cursor: onClick ? "pointer" : "default",
      }}
    >
      <span style={{ fontSize: 17, width: 22, textAlign: "center" }}>{icon}</span>
      <span
        style={{
          flex: 1,
          fontFamily: "system-ui, sans-serif",
          fontSize: 14.5,
          fontWeight: 500,
          color: danger ? "#D1493F" : t.ink,
        }}
      >
        {label}
      </span>
      {value}
    </div>
  );
}

function SettingsTab({ t, darkMode, setDarkMode, notifs, setNotifs, sound, setSound, onOpenProfile }) {
  return (
    <div style={{ flex: 1, overflowY: "auto" }}>
      <div
        onClick={() => onOpenProfile("me")}
        style={{
          display: "flex",
          alignItems: "center",
          gap: 14,
          padding: "16px",
          background: t.surface,
          margin: "4px 12px 14px",
          borderRadius: 18,
          cursor: "pointer",
        }}
      >
        <Avatar initial={ME.initial} gradient={ME.gradient} size={58} />
        <div style={{ flex: 1 }}>
          <div style={{ fontFamily: "'Baloo 2', system-ui, sans-serif", fontWeight: 700, fontSize: 17, color: t.ink }}>
            {ME.name}
          </div>
          <div style={{ fontSize: 12.5, color: t.muted, marginTop: 2 }}>{ME.status}</div>
        </div>
        <span style={{ color: t.muted, fontSize: 15 }}>›</span>
      </div>

      <SectionLabel t={t}>PREFERENCES</SectionLabel>
      <SettingsRow icon="🌙" label="Dark mode" t={t} value={<Toggle on={darkMode} onChange={setDarkMode} />} />
      <SettingsRow icon="🔔" label="Notifications" t={t} value={<Toggle on={notifs} onChange={setNotifs} />} />
      <SettingsRow icon="🔊" label="Message sounds" t={t} value={<Toggle on={sound} onChange={setSound} />} />

      <SectionLabel t={t}>PRIVACY</SectionLabel>
      <SettingsRow icon="🔒" label="Privacy & safety" t={t} value={<span style={{ color: t.muted }}>›</span>} />
      <SettingsRow icon="🚫" label="Blocked friends" t={t} value={<span style={{ color: t.muted }}>›</span>} />

      <SectionLabel t={t}>SUPPORT</SectionLabel>
      <SettingsRow icon="💬" label="Help center" t={t} value={<span style={{ color: t.muted }}>›</span>} />
      <SettingsRow icon="ℹ️" label="About Cantalk" t={t} value={<span style={{ color: t.muted, fontSize: 13 }}>v1.0.0</span>} />

      <div style={{ height: 8 }} />
      <SettingsRow icon="🚪" label="Log out" t={t} danger />
      <div style={{ height: 24 }} />
    </div>
  );
}

function ProfileSheet({ id, onClose, onStartChat, t }) {
  const person = id === "me" ? ME : CONTACTS[id];
  return (
    <div
      style={{
        position: "absolute",
        inset: 0,
        background: "rgba(20,19,24,0.45)",
        display: "flex",
        alignItems: "flex-end",
        zIndex: 20,
      }}
      onClick={onClose}
    >
      <div
        onClick={(e) => e.stopPropagation()}
        style={{
          width: "100%",
          background: t.surface,
          borderRadius: "24px 24px 0 0",
          padding: "10px 24px 28px",
        }}
      >
        <div style={{ width: 36, height: 4, background: t.border, borderRadius: 2, margin: "0 auto 18px" }} />
        <div style={{ display: "flex", flexDirection: "column", alignItems: "center", gap: 10 }}>
          <Avatar initial={person.initial} gradient={person.gradient} size={84} />
          <div style={{ fontFamily: "'Baloo 2', system-ui, sans-serif", fontWeight: 700, fontSize: 19, color: t.ink }}>
            {person.name}
          </div>
          <div style={{ fontSize: 13.5, color: t.muted }}>{person.status}</div>
        </div>
        {id !== "me" && (
          <button
            onClick={() => onStartChat(id)}
            style={{
              width: "100%",
              marginTop: 22,
              padding: "13px 0",
              borderRadius: 14,
              border: "none",
              background: `linear-gradient(135deg, ${BRAND_LIGHT} 0%, ${BRAND} 100%)`,
              color: "#FFFFFF",
              fontFamily: "'Baloo 2', system-ui, sans-serif",
              fontWeight: 700,
              fontSize: 15,
              cursor: "pointer",
            }}
          >
            Start chat
          </button>
        )}
      </div>
    </div>
  );
}

function ChatRoom({ id, onBack, t }) {
  const contact = CONTACTS[id];
  const [messages, setMessages] = useState(contact.messages);
  const [draft, setDraft] = useState("");
  const scrollRef = useRef(null);

  useEffect(() => {
    if (scrollRef.current) scrollRef.current.scrollTop = scrollRef.current.scrollHeight;
  }, [messages]);

  const send = () => {
    if (!draft.trim()) return;
    setMessages((m) => [...m, { from: "me", text: draft.trim(), time: "now" }]);
    setDraft("");
  };

  return (
    <div style={{ flex: 1, display: "flex", flexDirection: "column", minHeight: 0 }}>
      <div
        style={{
          display: "flex",
          alignItems: "center",
          gap: 10,
          padding: "10px 16px",
          background: t.bg,
          flexShrink: 0,
        }}
      >
        <button
          onClick={onBack}
          style={{ background: "none", border: "none", fontSize: 20, cursor: "pointer", color: t.ink, padding: 4 }}
          aria-label="Back"
        >
          ←
        </button>
        <Avatar initial={contact.initial} gradient={contact.gradient} size={34} online={contact.online} />
        <span style={{ fontFamily: "'Baloo 2', system-ui, sans-serif", fontWeight: 700, fontSize: 16, color: t.ink }}>
          {contact.name}
        </span>
      </div>

      <div
        ref={scrollRef}
        style={{
          flex: 1,
          overflowY: "auto",
          padding: "14px 14px 6px",
          background: t.bg,
          display: "flex",
          flexDirection: "column",
          gap: 8,
        }}
      >
        {messages.map((m, i) => (
          <div
            key={i}
            style={{
              display: "flex",
              justifyContent: m.from === "me" ? "flex-end" : "flex-start",
              alignItems: "flex-end",
              gap: 6,
            }}
          >
            {m.from === "me" && (
              <span style={{ fontSize: 10.5, color: t.muted, marginBottom: 2 }}>{m.time}</span>
            )}
            <div
              style={{
                maxWidth: "72%",
                padding: "9px 13px",
                borderRadius: m.from === "me" ? "16px 16px 4px 16px" : "16px 16px 16px 4px",
                background: m.from === "me" ? BRAND : t.bubbleThem,
                color: m.from === "me" ? "#FFFFFF" : t.bubbleThemText,
                border: m.from === "me" ? "none" : `1px solid ${t.border}`,
                fontSize: 14,
                lineHeight: 1.4,
              }}
            >
              {m.text}
            </div>
            {m.from === "them" && (
              <span style={{ fontSize: 10.5, color: t.muted, marginBottom: 2 }}>{m.time}</span>
            )}
          </div>
        ))}
      </div>

      <div style={{ display: "flex", gap: 8, padding: "10px 12px", background: t.surface, flexShrink: 0 }}>
        <input
          value={draft}
          onChange={(e) => setDraft(e.target.value)}
          onKeyDown={(e) => e.key === "Enter" && send()}
          placeholder="Message..."
          style={{
            flex: 1,
            border: `1px solid ${t.border}`,
            borderRadius: 20,
            padding: "10px 16px",
            fontSize: 14,
            outline: "none",
            fontFamily: "system-ui, sans-serif",
            background: t.bg,
            color: t.ink,
          }}
        />
        <button
          onClick={send}
          style={{
            width: 40,
            height: 40,
            borderRadius: "50%",
            border: "none",
            background: `linear-gradient(135deg, ${BRAND_LIGHT} 0%, ${BRAND} 100%)`,
            color: "#FFFFFF",
            fontSize: 16,
            cursor: "pointer",
            flexShrink: 0,
          }}
          aria-label="Send"
        >
          ➤
        </button>
      </div>
    </div>
  );
}

// ---------- app root ----------

export default function CantalkApp() {
  const [tab, setTab] = useState("friends");
  const [profileId, setProfileId] = useState(null);
  const [chatId, setChatId] = useState(null);
  const [darkMode, setDarkMode] = useState(false);
  const [notifs, setNotifs] = useState(true);
  const [sound, setSound] = useState(true);

  const t = darkMode ? THEME.dark : THEME.light;

  return (
    <div
      style={{
        width: "100%",
        maxWidth: 380,
        height: 740,
        margin: "0 auto",
        background: t.bg,
        borderRadius: 32,
        border: "8px solid #24232B",
        overflow: "hidden",
        display: "flex",
        flexDirection: "column",
        position: "relative",
        boxShadow: "0 20px 45px rgba(36,35,43,0.25)",
        fontFamily: "system-ui, sans-serif",
        transition: "background 0.2s ease",
      }}
    >
      <style>{`@import url('https://fonts.googleapis.com/css2?family=Baloo+2:wght@600;700;800&display=swap');`}</style>

      <StatusBar t={t} />

      {chatId ? (
        <ChatRoom id={chatId} onBack={() => setChatId(null)} t={t} />
      ) : (
        <>
          <TopBar
            title={tab}
            t={t}
            onSettings={() => setTab("settings")}
          />
          {tab === "friends" && <FriendsTab onOpenProfile={setProfileId} t={t} />}
          {tab === "chats" && <ChatsTab onOpenChat={setChatId} t={t} />}
          {tab === "settings" && (
            <SettingsTab
              t={t}
              darkMode={darkMode}
              setDarkMode={setDarkMode}
              notifs={notifs}
              setNotifs={setNotifs}
              sound={sound}
              setSound={setSound}
              onOpenProfile={setProfileId}
            />
          )}
          <BottomNav tab={tab} setTab={setTab} t={t} />
        </>
      )}

      {profileId && (
        <ProfileSheet
          id={profileId}
          onClose={() => setProfileId(null)}
          onStartChat={(id) => {
            setProfileId(null);
            setChatId(id);
          }}
          t={t}
        />
      )}
    </div>
  );
}
