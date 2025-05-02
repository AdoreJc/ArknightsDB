# RL04ClassicEndingStatsFragmentViewModel

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `Int32 fragmentTotalCnt`


## Methods

- `Int32 _CompareFragmentType(RoguelikeFragmentType, RoguelikeFragmentType)`

- `Int32 <LoadData>b__3_0(KeyValuePair`2, KeyValuePair`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04ClassicEndingStatsFragmentViewModel : RoguelikeClassicEndingStatsViewComponentModel
{
	private static readonly Dictionary`2 FRAGMENT_SORT_MAP; // 0x0
	public ListDict`2 fragmentItemModelList; // 0x10
	public Int32 fragmentTotalCnt; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0__CompareFragmentType; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2b11af0 VA: 0x7595129af0
	public override Void LoadData(String topicId, EndingResult result) { }
	// RVA: 0x2b12030 VA: 0x759512a030
	private Int32 _CompareFragmentType(RoguelikeFragmentType a, RoguelikeFragmentType b) { }
	// RVA: 0x2b12144 VA: 0x759512a144
	public Void .ctor() { }
	// RVA: 0x2b12218 VA: 0x759512a218
	private static Void .cctor() { }
	// RVA: 0x2b12340 VA: 0x759512a340
	private Int32 <LoadData>b__3_0(KeyValuePair`2 a, KeyValuePair`2 b) { }
}
```