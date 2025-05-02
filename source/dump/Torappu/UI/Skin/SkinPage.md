# SkinPage

**Namespace:** `Torappu.UI.Skin`


## Fields

- `UIRenderTextureImage _bkgBlur`


## Methods

- `IEnumerator <>n__0(Boolean)`

- `IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean)`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Skin
public class SkinPage : StateEnginePage
{
	private UIRenderTextureImage _bkgBlur; // 0xe8
	private static DelegateBridge __Hotfix0_EffectsOnShow; // 0x0
	private static DelegateBridge __Hotfix0_OpenPageForTargetSkin; // 0x8
	private static DelegateBridge __Hotfix0_OpenPageForTargetSkinList; // 0x10
	private static DelegateBridge __Hotfix0_OpenPageForCharList; // 0x18
	private static DelegateBridge __Hotfix0__OpenPageForTargetSkinWithData; // 0x20
	private static DelegateBridge __Hotfix0_OpenPageForSkinList; // 0x28
	private static DelegateBridge __Hotfix0_OpenPageForVoucherSkinList; // 0x30
	private static DelegateBridge __Hotfix0_OpenPageForMultiSkinList; // 0x38
	private static DelegateBridge __Hotfix0_OnCreate; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x23cde7c VA: 0x75949e5e7c
	protected override IEnumerator EffectsOnShow(Boolean isFromStack) { }
	// RVA: 0x23cdf6c VA: 0x75949e5f6c
	public static Void OpenPageForTargetSkin(String skinId) { }
	// RVA: 0x23cebcc VA: 0x75949e6bcc
	public static Void OpenPageForTargetSkinList(String focusId, List`1 skinIdList) { }
	// RVA: 0x23ced04 VA: 0x75949e6d04
	public static Void OpenPageForCharList(String charId) { }
	// RVA: 0x23cee00 VA: 0x75949e6e00
	private static Void _OpenPageForTargetSkinWithData(String charId, List`1 goodList) { }
	// RVA: 0x23cf030 VA: 0x75949e7030
	public static Void OpenPageForSkinList(String focusSkinId, List`1 skinList) { }
	// RVA: 0x23cf278 VA: 0x75949e7278
	public static Void OpenPageForVoucherSkinList(String focusSkinId, List`1 skinList, String voucherId, Int32 voucherInstId) { }
	// RVA: 0x23cf4f4 VA: 0x75949e74f4
	public static Void OpenPageForMultiSkinList(String focusSkinId, List`1 shopSkinList, List`1 skinIdList) { }
	// RVA: 0x23cf650 VA: 0x75949e7650
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x23cf8b4 VA: 0x75949e78b4
	public Void .ctor() { }
	// RVA: 0x23cf924 VA: 0x75949e7924
	private IEnumerator <>n__0(Boolean isFromStack) { }
	// RVA: 0x23cf930 VA: 0x75949e7930
	private IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean P0) { }
	// RVA: 0x23cf93c VA: 0x75949e793c
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
}
```