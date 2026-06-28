# CS 340 Portfolio — Client/Server Development

## Project Two: Grazioso Salvare Rescue Animal Dashboard

This repository contains my Project Two dashboard code and CRUD Python module from CS 340. The dashboard was built with Python, Dash, and MongoDB to help Grazioso Salvare filter and identify rescue animal candidates.

---

## Reflection

**How do you write programs that are maintainable, readable, and adaptable?**

I keep things separated. The CRUD module from Project One did one job, handle database operations and nothing else knew how it worked internally. When I hooked it into the Project Two dashboard I didn't have to rewrite anything, I just imported it and called the methods. That made debugging straightforward too. If something broke I knew immediately which layer to look at. That module could be dropped into any other Python project that needs MongoDB an API, a pipeline, whatever — and it would work without changes.

**How do you approach a problem as a computer scientist?**

I figure out what the data needs to support before I write anything. For this project that meant understanding what Grazioso Salvare actually needed to filter on before touching the schema or queries. A lot of coursework hands you clean data and tells you what to do with it. This was different, I had to think about how they actually use the information and build toward that. I'd take the same approach going forward: understand the questions the client needs to answer, then build the database to answer them efficiently.

**What do computer scientists do, and why does it matter?**

We build tools that let people do things faster than they could manually. For Grazioso Salvare, filtering rescue animal candidates by breed, age, and location in real time is a lot better than someone going through spreadsheets by hand. That's time that goes back into actual rescue work. The software isn't the point, placing dogs with search and rescue teams is the point. The software just makes it feasible.
