# HomeThemePrefab

**Namespace:** `Torappu.UI.Home.Theme`


## Fields

- `PrefabDisplay _prefab`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home.Theme
public class HomeThemePrefab : HomeThemeUIElem`1
{
	private PrefabDisplay _prefab; // 0x30
	private static DelegateBridge __Hotfix0_OnFillUIData; // 0x0
	private static DelegateBridge __Hotfix0_OnGenData; // 0x8
	private static DelegateBridge __Hotfix0_OnUIApply; // 0x10
	private static DelegateBridge __Hotfix0_OnClearRef; // 0x18
	private static DelegateBridge __Hotfix0_OnApplyEmpty; // 0x20
	private static DelegateBridge __Hotfix0_OnPrefabApplied; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x284d060 VA: 0x7594e65060
	protected sealed override Void OnFillUIData(HomeThemePrefabData data, AssetPathConvertor pathConvertor) { }
	// RVA: 0x284d168 VA: 0x7594e65168
	public override Void OnGenData() { }
	// RVA: 0x284d1fc VA: 0x7594e651fc
	protected sealed override Void OnUIApply(HomeThemePrefabData data, HomeTheme theme) { }
	// RVA: 0x284d334 VA: 0x7594e65334
	protected override Void OnClearRef() { }
	// RVA: 0x284d40c VA: 0x7594e6540c
	protected override Void OnApplyEmpty() { }
	// RVA: 0x284cf58 VA: 0x7594e64f58
	protected virtual Void OnPrefabApplied(GameObject inst) { }
	// RVA: 0x284cec4 VA: 0x7594e64ec4
	public Void .ctor() { }
}
```