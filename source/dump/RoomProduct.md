# RoomProduct

**Namespace:** ` `


## Fields

- `Clue m_clue`


## Properties

- `IMeetingClue clue`

- `Int32 creditPerClue`


## Methods

- `IMeetingClue get_clue()`

- `Int32 get_creditPerClue()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RoomProduct : IRoomClueProduct, IHotfixable
{
	private Clue m_clue; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_clue; // 0x8
	private static DelegateBridge __Hotfix0_get_creditPerClue; // 0x10

	public IMeetingClue clue { get; }
	public Int32 creditPerClue { get; }

	// RVA: 0x3de1ef0 VA: 0x75963f9ef0
	public Void .ctor(PlayerBuildingMeetingClue clue, SpriteHub clueHub) { }
	// RVA: 0x3de7538 VA: 0x75963ff538
	public IMeetingClue get_clue() { }
	// RVA: 0x3de75a0 VA: 0x75963ff5a0
	public Int32 get_creditPerClue() { }
}
```