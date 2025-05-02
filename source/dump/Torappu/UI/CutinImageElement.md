# CutinImageElement

**Namespace:** `Torappu.UI`


## Fields

- `Transform _offset`

- `Image _img`

- `UIStencilComponent _stencilComp`


## Methods

- `String _EnsureResPath(ParamType, String)`

- `Void _SetStencilComp(CutinElementParam)`

- `Void ClearElement()`

- `Void <SetCutinElement>b__4_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class CutinImageElement : CutinElement, IHotfixable
{
	private Transform _offset; // 0x18
	private Image _img; // 0x20
	private UIStencilComponent _stencilComp; // 0x28
	private const Single DEFAULT_FADE_DURATION; // 0x0
	private static DelegateBridge __Hotfix0_SetCutinElement; // 0x0
	private static DelegateBridge __Hotfix0__EnsureResPath; // 0x8
	private static DelegateBridge __Hotfix0__SetStencilComp; // 0x10
	private static DelegateBridge __Hotfix0_DoMove; // 0x18
	private static DelegateBridge __Hotfix0_DoScale; // 0x20
	private static DelegateBridge __Hotfix0_ClearElement; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x216db90 VA: 0x7594785b90
	public override Tween SetCutinElement(CutinElementParam param, ILoadAsset assetLoader) { }
	// RVA: 0x216df4c VA: 0x7594785f4c
	private String _EnsureResPath(ParamType type, String spriteName) { }
	// RVA: 0x216debc VA: 0x7594785ebc
	private Void _SetStencilComp(CutinElementParam param) { }
	// RVA: 0x216e02c VA: 0x759478602c
	public override Tween DoMove(Vector3 fromPos, Vector3 toPos, Single duration) { }
	// RVA: 0x216e134 VA: 0x7594786134
	public override Tween DoScale(Vector3 scaleFrom, Vector3 scaleTo, Single duration) { }
	// RVA: 0x216e250 VA: 0x7594786250
	public Void ClearElement() { }
	// RVA: 0x216e314 VA: 0x7594786314
	public Void .ctor() { }
	// RVA: 0x216e380 VA: 0x7594786380
	private Void <SetCutinElement>b__4_0() { }
}
```