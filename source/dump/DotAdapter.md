# DotAdapter

**Namespace:** ` `


## Fields

- `EmoticonPagerPanelView m_closure`


## Methods

- `Void SampleDotAnim(Single)`

- `Void _SampleDot(Int32, Single, GameObject)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DotAdapter : SimpleLayoutAdapter
{
	private EmoticonPagerPanelView m_closure; // 0x20
	private const String DOT_TWEEN_ANIM_NAME; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10
	private static DelegateBridge __Hotfix0_SampleDotAnim; // 0x18
	private static DelegateBridge __Hotfix0__SampleDot; // 0x20

	public override Int32 count { get; }

	// RVA: 0x29b8d34 VA: 0x7594fd0d34
	public Void .ctor(EmoticonPagerPanelView closure) { }
	// RVA: 0x29b94b8 VA: 0x7594fd14b8
	public override Int32 get_count() { }
	// RVA: 0x29b9598 VA: 0x7594fd1598
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x29b8b80 VA: 0x7594fd0b80
	public Void SampleDotAnim(Single curValue) { }
	// RVA: 0x29b96e8 VA: 0x7594fd16e8
	private Void _SampleDot(Int32 position, Single curValue, GameObject obj) { }
}
```