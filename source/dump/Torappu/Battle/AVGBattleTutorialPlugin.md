# AVGBattleTutorialPlugin

**Namespace:** `Torappu.Battle`


## Fields

- `UICanvasScalerHelper m_helper`


## Methods

- `Void RegisterExtraTarget(String, GameObject)`

- `Void OnReset()`

- `Void _InitIfNot()`

- `Boolean TryGetInputBlockerPos(Command, ref)`

- `Boolean TryGetFocusPos(Command, ref, ref)`

- `Boolean TryGetPos(Command, ref)`

- `Boolean TryGetDragPos(Command, ref, Boolean)`

- `Boolean _TryGetCardListPos(Command, String, String, ref)`

- `Boolean _TryGetTilePos(Command, String, String, ref)`

- `Boolean _TryGetTargetPos(Command, String, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AVGBattleTutorialPlugin : IAVGTutorialPanelPlugin
{
	private const String CARD_INDEX; // 0x0
	private const String CARD_START_ANCHOR; // 0x0
	private const String CARD_INDEX_START; // 0x0
	private const String CARD_START_ANCHOR_START; // 0x0
	private const String CARD_INDEX_END; // 0x0
	private const String CARD_START_ANCHOR_END; // 0x0
	private const String TILE_X; // 0x0
	private const String TILE_Y; // 0x0
	private const String START_TILE_X; // 0x0
	private const String START_TILE_Y; // 0x0
	private const String END_TILE_X; // 0x0
	private const String END_TILE_Y; // 0x0
	private const String BATTLE_TARGET; // 0x0
	private const String START_BATTLE_TARGET; // 0x0
	private const String END_BATTLE_TARGET; // 0x0
	private Dictionary`2 m_targetPool; // 0x10
	private UICanvasScalerHelper m_helper; // 0x18


	// RVA: 0x1c47410 VA: 0x759425f410
	public Void .ctor() { }
	// RVA: 0x1c47498 VA: 0x759425f498
	public Void RegisterExtraTarget(String name, GameObject target) { }
	// RVA: 0x1c47500 VA: 0x759425f500
	public Void OnReset() { }
	// RVA: 0x1c47550 VA: 0x759425f550
	private Void _InitIfNot() { }
	// RVA: 0x1c47668 VA: 0x759425f668
	public Boolean TryGetInputBlockerPos(Command command, ref Vector2 pos) { }
	// RVA: 0x1c47860 VA: 0x759425f860
	public Boolean TryGetFocusPos(Command command, ref Vector3 pos, ref AnchorType ancher) { }
	// RVA: 0x1c47744 VA: 0x759425f744
	private Boolean TryGetPos(Command command, ref Vector3 pos) { }
	// RVA: 0x1c47fe4 VA: 0x759425ffe4
	public Boolean TryGetDragPos(Command command, ref Vector2 pos, Boolean isStartPos) { }
	// RVA: 0x1c47938 VA: 0x759425f938
	private Boolean _TryGetCardListPos(Command command, String cardIndexFlag, String cardStartDirectionFlag, ref Vector2 pos) { }
	// RVA: 0x1c47bcc VA: 0x759425fbcc
	private Boolean _TryGetTilePos(Command command, String tilePosX, String tilePosY, ref Vector2 pos) { }
	// RVA: 0x1c47dd4 VA: 0x759425fdd4
	private Boolean _TryGetTargetPos(Command command, String targetKey, ref Vector2 pos) { }
}
```