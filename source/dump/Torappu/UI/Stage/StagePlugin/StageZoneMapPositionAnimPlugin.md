# StageZoneMapPositionAnimPlugin

**Namespace:** `Torappu.UI.Stage.StagePlugin`


## Fields

- `UIAnimationLocation _anim`

- `Boolean _fixOnBackground`

- `GameObject _imageGroup`

- `RectTransform m_rectTrans`

- `Vector2 m_startPos`

- `AnimationWrapper m_animWrapper`

- `String m_animName`

- `Single m_animLength`


## Methods

- `Void _UpdateAnim(MapPosInfo)`

- `Void _UpdateImagePosition(MapPosInfo)`

- `Void <>xLuaBaseProxy_OnMapInitiated(MapPosInfo)`

- `Void <>xLuaBaseProxy_OnMapPositionChanged(MapPosInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.StagePlugin
public class StageZoneMapPositionAnimPlugin : StageMainZoneMapPlugin
{
	private UIAnimationLocation _anim; // 0x18
	private Boolean _fixOnBackground; // 0x28
	private GameObject _imageGroup; // 0x30
	private RectTransform m_rectTrans; // 0x38
	private Vector2 m_startPos; // 0x40
	private AnimationWrapper m_animWrapper; // 0x48
	private String m_animName; // 0x50
	private Single m_animLength; // 0x58
	private static DelegateBridge __Hotfix0_OnMapInitiated; // 0x0
	private static DelegateBridge __Hotfix0__UpdateAnim; // 0x8
	private static DelegateBridge __Hotfix0__UpdateImagePosition; // 0x10
	private static DelegateBridge __Hotfix0_OnMapPositionChanged; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2fe0768 VA: 0x75955f8768
	public override Void OnMapInitiated(MapPosInfo posInfo) { }
	// RVA: 0x2fe09c0 VA: 0x75955f89c0
	private Void _UpdateAnim(MapPosInfo posInfo) { }
	// RVA: 0x2fe0b04 VA: 0x75955f8b04
	private Void _UpdateImagePosition(MapPosInfo posInfo) { }
	// RVA: 0x2fe0bc4 VA: 0x75955f8bc4
	public override Void OnMapPositionChanged(MapPosInfo posInfo) { }
	// RVA: 0x2fe0cc4 VA: 0x75955f8cc4
	public Void .ctor() { }
	// RVA: 0x2fe0d3c VA: 0x75955f8d3c
	private Void <>xLuaBaseProxy_OnMapInitiated(MapPosInfo P0) { }
	// RVA: 0x2fe0d44 VA: 0x75955f8d44
	private Void <>xLuaBaseProxy_OnMapPositionChanged(MapPosInfo P0) { }
}
```