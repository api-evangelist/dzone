---
title: "Seeding Postgres When Your Schema Has Foreign-Key Cycles"
url: "https://dzone.com/articles/three-strategies-for-seeding-postgres"
date: "2026-07-17"
author: "Mikhail Shytsko"
feed_url: "https://feeds.dzone.com/home"
---
I have lost more afternoons than I would like to admit on this exact problem: a seed script that ran cleanly yesterday now crashes on its first INSERT , and the error message tells you something you already knew, namely that you have a chicken-and-egg dependency between two tables. SQL ERROR: insert or update on table "users" violates foreign key constraint "users_organization_id_fkey" DETAIL: Key (organization_id)=(1) is not present in table "organizations". The natural next move is to reorder the inserts, putting organizations first, except that organizations.owner_user_id is NOT NULL REFERE
