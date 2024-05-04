# Fifa 2024 Teams

This repository is made for my personal project, feel free to clone it and change it to uour liking.

## How to use

Fetch the teams from the repository and parse it to json.

```typescript
const response = await fetch("https://raw.githubusercontent.com/pawix135/fifa24-teams/main/teams.json");
const teams = (await fifa.json()) as Team[];
```

The team interface is as follows:

```typescript
interface Team {
  teamName: string;
  teamid: string;
  url: string;
}
```

All the images are not mine and are taken from the internet, if you are the owner of the image and want me to remove it, please contact me!
