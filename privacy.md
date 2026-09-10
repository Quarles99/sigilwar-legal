# Sigilwar — Privacy Policy

**Last updated: 10 September 2026**

This policy explains what data the Sigilwar Discord bot ("the Bot"), operated by
**Quarles**, collects, why it is held, and how to have it removed.

The short version: the Bot stores Discord's numeric IDs and the game progress
attached to them. It does not store your name, email address, avatar, or any
message you send. It cannot read your messages.

## 1. What we collect

Everything below is created either by Discord's own interaction data or by you
playing the game.

**Discord identifiers**

- **Your Discord user ID** — the numeric ID Discord assigns your account. This is
  how the Bot knows which characters, gold and items are yours. It is not your
  username, display name or email.
- **Server (guild) IDs** — recorded against player-versus-player fights, so that
  a server's leaderboard can show fights that happened in that server.

**Game data**

- Characters: names you choose, class, level, experience, health and mana, and
  creation time.
- Progress and economy: gold, inventory, gear and its rolled bonuses, which item
  is in which equipment slot, shop reroll counters, and purchased storage and
  character slots.
- Activity state: which monster a character is hunting, when it started, and when
  its resources were last updated.
- Player-versus-player records: which characters fought, who won, when, the
  server it happened in, and the text of the combat narration, so the fight can
  be shown again from the button on the message.
- Matchmaking ratings.

**What we do not collect**

- Message content. The Bot does not request Discord's Message Content intent and
  cannot read what you write.
- Usernames, display names, email addresses, avatars, or phone numbers.
- IP addresses, cookies, tracking identifiers, or analytics of any kind. The Bot
  has no website and serves no pages.
- Server member lists. When the Bot needs to know whether a particular player is
  still in a server — before allowing an attack on their character — it asks
  Discord at that moment and does not keep the answer.
- Voice data, attachments, or anything from channels the Bot is not directly
  commanded in.

## 2. Character names are public and are your own free text

You choose your character names, and they are shown to other players: on the
server leaderboard, in the public `/flex` card, in the list of attackable
opponents, and in combat playback in the channel. Do not put personal
information into a character name — anything you put there is published to
everyone who can see that channel.

## 3. Online status

If the server operator has enabled it, the Bot may check whether you appear
online or idle in Discord, for one purpose only: to end a long watched combat
session early when nobody appears to be watching it. This is read at that moment
and **never stored**. The feature is optional and the Bot works normally without
it.

## 4. Why we hold this data

Sigilwar is an idle game: progress accrues over hours and days while you are
away, so characters, resources and timestamps have to be stored between sessions
for the game to function at all. Server IDs are held so that a leaderboard can be
limited to the server it belongs to. Combat narration is held so an already
resolved fight can be displayed again exactly as it happened.

We have no other purpose for it. We do not profile you, advertise to you, or
attempt to identify you.

## 5. Who we share it with

Nobody. We do not sell, rent, or share your data with third parties. There are no
advertisers, analytics providers, or data brokers involved.

Data is sent back to Discord only in the ordinary sense that the Bot's replies —
your character sheet, a leaderboard, a fight — are delivered as Discord messages.
Discord's own privacy policy governs that: https://discord.com/privacy

## 6. Where it is stored

Game data is stored in a single SQLite database file on a server controlled by
the operator. Access is restricted to the operator.

## 7. Retention

Game data is kept for as long as you use the Bot, because it is your progress. It
may also be removed at any time under the Terms of Service — the game is in
development and data may be reset or migrated.

## 8. Deleting your data

Email **quarlesdev@gmail.com** from an address you can be reached at, including your
Discord user ID, and we will delete all data associated with it within **30
days**. Deletion is permanent: characters, gear, gold and ratings cannot be
recovered afterwards.

You may also ask us what data is held about you, and we will provide it in the
same timeframe. Depending on where you live you may have further rights over your
data, including correction and objection; contact us and we will honour them.

## 9. Children

The Bot is not directed at children below Discord's minimum age. If we learn that
data belongs to someone below that age, we will delete it.

## 10. Changes to this policy

We may update this policy. The date at the top shows when it last changed.

## 11. Contact

**quarlesdev@gmail.com**
