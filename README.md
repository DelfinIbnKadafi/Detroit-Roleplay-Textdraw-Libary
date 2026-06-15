new Text: BACKGROUND_HBE[3];

BACKGROUND_HBE[0] = TextDrawCreate(567.000, 381.000, "LD_SPAC:white");
TextDrawTextSize(BACKGROUND_HBE[0], 98.000, 105.000);
TextDrawAlignment(BACKGROUND_HBE[0], TEXT_DRAW_ALIGN_LEFT);
TextDrawColour(BACKGROUND_HBE[0], 150);
TextDrawSetShadow(BACKGROUND_HBE[0], 0);
TextDrawSetOutline(BACKGROUND_HBE[0], 0);
TextDrawBackgroundColour(BACKGROUND_HBE[0], 255);
TextDrawFont(BACKGROUND_HBE[0], TEXT_DRAW_FONT_SPRITE_DRAW);
TextDrawSetProportional(BACKGROUND_HBE[0], true);

BACKGROUND_HBE[1] = TextDrawCreate(575.000, 391.000, "HUD:radar_burgerShot");
TextDrawTextSize(BACKGROUND_HBE[1], 19.000, 25.000);
TextDrawAlignment(BACKGROUND_HBE[1], TEXT_DRAW_ALIGN_LEFT);
TextDrawColour(BACKGROUND_HBE[1], -1);
TextDrawSetShadow(BACKGROUND_HBE[1], 0);
TextDrawSetOutline(BACKGROUND_HBE[1], 0);
TextDrawBackgroundColour(BACKGROUND_HBE[1], 255);
TextDrawFont(BACKGROUND_HBE[1], TEXT_DRAW_FONT_SPRITE_DRAW);
TextDrawSetProportional(BACKGROUND_HBE[1], true);

BACKGROUND_HBE[2] = TextDrawCreate(575.000, 419.000, "HUD:radar_diner");
TextDrawTextSize(BACKGROUND_HBE[2], 18.000, 27.000);
TextDrawAlignment(BACKGROUND_HBE[2], TEXT_DRAW_ALIGN_LEFT);
TextDrawColour(BACKGROUND_HBE[2], -1);
TextDrawSetShadow(BACKGROUND_HBE[2], 0);
TextDrawSetOutline(BACKGROUND_HBE[2], 0);
TextDrawBackgroundColour(BACKGROUND_HBE[2], 255);
TextDrawFont(BACKGROUND_HBE[2], TEXT_DRAW_FONT_SPRITE_DRAW);
TextDrawSetProportional(BACKGROUND_HBE[2], true);

####################################################################################################

new PlayerText: STATS[MAX_PLAYERS][2];

STATS[playerid][0] = CreatePlayerTextDraw(playerid, 601.000, 398.000, "100");
PlayerTextDrawLetterSize(playerid, STATS[playerid][0], 0.300, 1.500);
PlayerTextDrawAlignment(playerid, STATS[playerid][0], TEXT_DRAW_ALIGN_LEFT);
PlayerTextDrawColour(playerid, STATS[playerid][0], -1);
PlayerTextDrawSetShadow(playerid, STATS[playerid][0], 1);
PlayerTextDrawSetOutline(playerid, STATS[playerid][0], 1);
PlayerTextDrawBackgroundColour(playerid, STATS[playerid][0], 150);
PlayerTextDrawFont(playerid, STATS[playerid][0], TEXT_DRAW_FONT_1);
PlayerTextDrawSetProportional(playerid, STATS[playerid][0], true);

STATS[playerid][1] = CreatePlayerTextDraw(playerid, 601.000, 426.000, "100");
PlayerTextDrawLetterSize(playerid, STATS[playerid][1], 0.300, 1.500);
PlayerTextDrawAlignment(playerid, STATS[playerid][1], TEXT_DRAW_ALIGN_LEFT);
PlayerTextDrawColour(playerid, STATS[playerid][1], -1);
PlayerTextDrawSetShadow(playerid, STATS[playerid][1], 1);
PlayerTextDrawSetOutline(playerid, STATS[playerid][1], 1);
PlayerTextDrawBackgroundColour(playerid, STATS[playerid][1], 150);
PlayerTextDrawFont(playerid, STATS[playerid][1], TEXT_DRAW_FONT_1);
PlayerTextDrawSetProportional(playerid, STATS[playerid][1], true);

