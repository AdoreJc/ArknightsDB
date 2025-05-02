# Act1ArcadeSettlementIllustView

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `UICharacterIllust m_cacheIllust`


## Methods

- `Void OnRender(CharUISkinStruct, Rank)`

- `Void _PlayIllustVoice(CharUISkinStruct, Rank)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeSettlementIllustView : MonoBehaviour, IHotfixable
{
	private UICharacterIllust m_cacheIllust; // 0x18
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0__PlayIllustVoice; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x34060c8 VA: 0x7595a1e0c8
	public Void OnRender(CharUISkinStruct skin, Rank rank) { }
	// RVA: 0x3406258 VA: 0x7595a1e258
	private Void _PlayIllustVoice(CharUISkinStruct skin, Rank rank) { }
	// RVA: 0x34064e0 VA: 0x7595a1e4e0
	public Void .ctor() { }
}
```