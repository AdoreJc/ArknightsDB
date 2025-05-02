# GainCardTrigger

**Namespace:** `Torappu.Battle`


## Fields

- `String _cardKey`

- `Boolean _releaseDiscardIfAllUsedUp`

- `LegionGameMode m_gameMode`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class GainCardTrigger : TargetTrigger
{
	private String _cardKey; // 0x20
	private Boolean _releaseDiscardIfAllUsedUp; // 0x28
	private LegionGameMode m_gameMode; // 0x30

	public override Entity target { get; }
	public override Boolean isReadyToTrig { get; }

	// RVA: 0x1bd6db0 VA: 0x75941eedb0
	public override Entity get_target() { }
	// RVA: 0x1bd6db8 VA: 0x75941eedb8
	public override Boolean get_isReadyToTrig() { }
	// RVA: 0x1bd6dc0 VA: 0x75941eedc0
	public override Boolean Search(Boolean force) { }
	// RVA: 0x1bd702c VA: 0x75941ef02c
	public override Boolean CheckTargetIn(ILocatable target) { }
	// RVA: 0x1bd7034 VA: 0x75941ef034
	public Void .ctor() { }
}
```