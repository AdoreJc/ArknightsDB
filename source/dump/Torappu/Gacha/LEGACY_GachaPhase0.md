# LEGACY_GachaPhase0

**Namespace:** `Torappu.Gacha`


## Fields

- `Single _earlyExitTime`

- `Single _delayToDisable`

- `SkeletonGraphic _skeleton`


## Methods

- `Void <Play>b__6_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Gacha
public class LEGACY_GachaPhase0 : GachaPhase
{
	private Single _earlyExitTime; // 0x18
	private Single _delayToDisable; // 0x1c
	private SkeletonGraphic _skeleton; // 0x20
	private String[] _animations; // 0x28
	private static DelegateBridge __Hotfix0_get_canSkip; // 0x0
	private static DelegateBridge __Hotfix0_Play; // 0x8
	private static DelegateBridge __Hotfix0_SkipToEnd; // 0x10
	private static DelegateBridge __Hotfix0_PreloadSounds; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override Boolean canSkip { get; }

	// RVA: 0x37015f8 VA: 0x7595d195f8
	public override Boolean get_canSkip() { }
	// RVA: 0x3701660 VA: 0x7595d19660
	public override IEnumerator Play(GachaController controller, PlayMode playMode) { }
	// RVA: 0x3701760 VA: 0x7595d19760
	public override Void SkipToEnd(GachaController controller, PlayMode playMode) { }
	// RVA: 0x37017f4 VA: 0x7595d197f4
	public override Void PreloadSounds(PlayMode playMode, RarityRank rarity, Boolean isMultipleGacha) { }
	// RVA: 0x37018e4 VA: 0x7595d198e4
	public Void .ctor() { }
	// RVA: 0x370199c VA: 0x7595d1999c
	private Void <Play>b__6_0() { }
}
```