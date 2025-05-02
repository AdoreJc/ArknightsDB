# TermDescription

**Namespace:** `Torappu.UI`


## Fields

- `RectTransform termDesciptionRoot`


## Methods

- `Void ShowTermDesc(UITermDescDataModel)`

- `Void _InitTermDescViewIfNeeded()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class TermDescription : SingletonMonoBehaviour`1, ISingletonNotAutoCreate, ILuaCallCSharp, IHotfixable
{
	private RectTransform termDesciptionRoot; // 0x18
	private static TermDescriptionView m_cachedTermDescView; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge __Hotfix0_ShowTermDesc; // 0x18
	private static DelegateBridge __Hotfix0__InitTermDescViewIfNeeded; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x228be14 VA: 0x75948a3e14
	protected override Void OnInit() { }
	// RVA: 0x228be94 VA: 0x75948a3e94
	protected override Void OnDestroy() { }
	// RVA: 0x228bf14 VA: 0x75948a3f14
	public Void ShowTermDesc(UITermDescDataModel valuePair) { }
	// RVA: 0x228c040 VA: 0x75948a4040
	private Void _InitTermDescViewIfNeeded() { }
	// RVA: 0x228c6b0 VA: 0x75948a46b0
	public Void .ctor() { }
}
```