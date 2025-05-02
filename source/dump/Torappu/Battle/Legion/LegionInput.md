# LegionInput

**Namespace:** `Torappu.Battle.Legion`


## Fields

- `Int32 gBuffDyingDuration`

- `Boolean initRandomShuffle`

- `Boolean recycleRandomShuffle`

- `Int32 initCardCount`

- `Int32 initRedrawCount`

- `Int32 ingameRedrawCount`

- `Int32 goldForEndprepare`

- `Int32 goldForWaveEnd`

- `Int32 maxGold`

- `Int32 initGold`

- `Int32 initCardPrice`

- `Int32 cardPriceGrowth`

- `Int32 maxCardPrice`

- `Int32 initReShuffleTimes`

- `Int32 initReShuffleCostTotal`

- `Int32 initReShufflePioneerCount`

- `Int32 addPriceWhenReshuffle`

- `Int32 maxAddPriceWhenReshuffle`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Legion
public class LegionInput : IHotfixable
{
	public List`1 professionSkillPart; // 0x10
	public List`1 trapInfos; // 0x18
	public readonly Int32 maxStackCntPerCategory; // 0x20
	public readonly Int32 professionLevelAdd; // 0x24
	public readonly Int32 maxCardCnt; // 0x28
	public Int32 gBuffDyingDuration; // 0x2c
	public Boolean initRandomShuffle; // 0x30
	public Boolean recycleRandomShuffle; // 0x31
	public Int32 initCardCount; // 0x34
	public Int32 initRedrawCount; // 0x38
	public Int32 ingameRedrawCount; // 0x3c
	public Int32 goldForEndprepare; // 0x40
	public Int32 goldForWaveEnd; // 0x44
	public Int32 maxGold; // 0x48
	public Int32 initGold; // 0x4c
	public Int32 initCardPrice; // 0x50
	public Int32 cardPriceGrowth; // 0x54
	public Int32 maxCardPrice; // 0x58
	public Int32 initReShuffleTimes; // 0x5c
	public Int32 initReShuffleCostTotal; // 0x60
	public Int32 initReShufflePioneerCount; // 0x64
	public Int32 addPriceWhenReshuffle; // 0x68
	public Int32 maxAddPriceWhenReshuffle; // 0x6c
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x1dc4f34 VA: 0x75943dcf34
	public Void .ctor() { }
}
```