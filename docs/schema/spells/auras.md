# auras

!!! info
	This page was last generated 2022.05.11

## Relationship Diagram

[Diagram Edit](https://mermaid.live/edit#eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgYXVyYXMge1xuICAgICAgICBpbnQgbnBjX3R5cGVcbiAgICAgICAgaW50IHNwZWxsX2lkXG4gICAgfVxuICAgIG5wY190eXBlcyB7XG4gICAgICAgIGludHVuc2lnbmVkIGFsdF9jdXJyZW5jeV9pZFxuICAgICAgICBpbnR1bnNpZ25lZCBtZXJjaGFudF9pZFxuICAgICAgICBpbnQgbnBjX2ZhY3Rpb25faWRcbiAgICAgICAgaW50dW5zaWduZWQgbnBjX3NwZWxsc19pZFxuICAgICAgICBpbnQgaWRcbiAgICAgICAgaW50dW5zaWduZWQgZW1vdGVpZFxuICAgICAgICBpbnR1bnNpZ25lZCBhcm1vcnRpbnRfaWRcbiAgICAgICAgaW50dW5zaWduZWQgbG9vdHRhYmxlX2lkXG4gICAgfVxuICAgIHNwZWxsc19uZXcge1xuICAgICAgICBpbnQgaWRcbiAgICB9XG4gICAgYXVyYXMgfHwtLW97IG5wY190eXBlcyA6IE9uZS10by1PbmVcbiAgICBhdXJhcyB8fC0tb3sgc3BlbGxzX25ldyA6IE9uZS10by1PbmVcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=){target=diagram-edit}

[![](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgYXVyYXMge1xuICAgICAgICBpbnQgbnBjX3R5cGVcbiAgICAgICAgaW50IHNwZWxsX2lkXG4gICAgfVxuICAgIG5wY190eXBlcyB7XG4gICAgICAgIGludHVuc2lnbmVkIGFsdF9jdXJyZW5jeV9pZFxuICAgICAgICBpbnR1bnNpZ25lZCBtZXJjaGFudF9pZFxuICAgICAgICBpbnQgbnBjX2ZhY3Rpb25faWRcbiAgICAgICAgaW50dW5zaWduZWQgbnBjX3NwZWxsc19pZFxuICAgICAgICBpbnQgaWRcbiAgICAgICAgaW50dW5zaWduZWQgZW1vdGVpZFxuICAgICAgICBpbnR1bnNpZ25lZCBhcm1vcnRpbnRfaWRcbiAgICAgICAgaW50dW5zaWduZWQgbG9vdHRhYmxlX2lkXG4gICAgfVxuICAgIHNwZWxsc19uZXcge1xuICAgICAgICBpbnQgaWRcbiAgICB9XG4gICAgYXVyYXMgfHwtLW97IG5wY190eXBlcyA6IE9uZS10by1PbmVcbiAgICBhdXJhcyB8fC0tb3sgc3BlbGxzX25ldyA6IE9uZS10by1PbmVcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=)](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgYXVyYXMge1xuICAgICAgICBpbnQgbnBjX3R5cGVcbiAgICAgICAgaW50IHNwZWxsX2lkXG4gICAgfVxuICAgIG5wY190eXBlcyB7XG4gICAgICAgIGludHVuc2lnbmVkIGFsdF9jdXJyZW5jeV9pZFxuICAgICAgICBpbnR1bnNpZ25lZCBtZXJjaGFudF9pZFxuICAgICAgICBpbnQgbnBjX2ZhY3Rpb25faWRcbiAgICAgICAgaW50dW5zaWduZWQgbnBjX3NwZWxsc19pZFxuICAgICAgICBpbnQgaWRcbiAgICAgICAgaW50dW5zaWduZWQgZW1vdGVpZFxuICAgICAgICBpbnR1bnNpZ25lZCBhcm1vcnRpbnRfaWRcbiAgICAgICAgaW50dW5zaWduZWQgbG9vdHRhYmxlX2lkXG4gICAgfVxuICAgIHNwZWxsc19uZXcge1xuICAgICAgICBpbnQgaWRcbiAgICB9XG4gICAgYXVyYXMgfHwtLW97IG5wY190eXBlcyA6IE9uZS10by1PbmVcbiAgICBhdXJhcyB8fC0tb3sgc3BlbGxzX25ldyA6IE9uZS10by1PbmVcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=){target=diagram}

## Relationships

| Relationship Type | Local Key | Relates to Table | Foreign Key |
| :--- | :--- | :--- | :--- |
| One-to-One | npc_type | [npc_types](../../schema/npcs/npc_types.md) | id |
| One-to-One | spell_id | [spells_new](../../schema/spells/spells_new.md) | id |


## Schema

| Column | Data Type | Description |
| :--- | :--- | :--- |
| type | int | Unique Aura Identifier |
| npc_type | int | [NPC Type Identifier](../../schema/npcs/npc_types.md) |
| name | varchar | Name |
| spell_id | int | [Spell Identifier](spells_new.md) |
| distance | int | Distance |
| aura_type | int | [Aura Type](../../../../server/spells/aura-types) |
| spawn_type | int | [Aura Spawn Type](../../../../server/spells/aura-spawn-types) |
| movement | int | [Aura Movement Type](../../../../server/spells/aura-movement-types) |
| duration | int | Duration |
| icon | int | Icon |
| cast_time | int | Cast Time |

