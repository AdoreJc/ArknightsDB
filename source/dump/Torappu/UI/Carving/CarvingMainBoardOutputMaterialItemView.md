# CarvingMainBoardOutputMaterialItemView

**Namespace:** `Torappu.UI.Carving`


## Fields

- `CarvingMaterialItem _materialItemPrefab`

- `RectTransform _materialContent`

- `Single _materialScaler`

- `UIParticle _uiParticle`

- `UIAnimationLocation _lightAnimLocation`

- `CarvingMaterialItem m_materialItem`

- `String m_cachedIconId`

- `Int32 m_cachedCnt`

- `Boolean m_isInited`

- `Tween m_lightTween`

- `Int32 m_cachedEnterBoardSeqNum`


## Methods

- `Void Render(CarvingMaterialModel, Boolean, Int32)`

- `Void _PlayLightAnim()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainBoardOutputMaterialItemView : MonoBehaviour, IHotfixable
{
	private CarvingMaterialItem _materialItemPrefab; // 0x18
	private RectTransform _materialContent; // 0x20
	private Single _materialScaler; // 0x28
	private UIParticle _uiParticle; // 0x30
	private UIAnimationLocation _lightAnimLocation; // 0x38
	private CarvingMaterialItem m_materialItem; // 0x48
	private String m_cachedIconId; // 0x50
	private Int32 m_cachedCnt; // 0x58
	private Boolean m_isInited; // 0x5c
	private Tween m_lightTween; // 0x60
	private Int32 m_cachedEnterBoardSeqNum; // 0x68
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__PlayLightAnim; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2d98914 VA: 0x75953b0914
	public Void Render(CarvingMaterialModel model, Boolean needStopTween, Int32 enterBoardSeqNum) { }
	// RVA: 0x2d98bb4 VA: 0x75953b0bb4
	private Void _PlayLightAnim() { }
	// RVA: 0x2d98ab0 VA: 0x75953b0ab0
	private Void _InitIfNot() { }
	// RVA: 0x2d98cc0 VA: 0x75953b0cc0
	public Void .ctor() { }
}
```