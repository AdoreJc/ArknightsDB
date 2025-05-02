# IllustHandler

**Namespace:** ` `


## Fields

- `HomeIllustView m_closure`


## Methods

- `Void ApplyIllustLayout(UIIllustLayoutInfo)`

- `CharUISkinStruct GetCurSkin()`

- `String GetIllustId()`

- `UIIllustLayoutInfo GetCurIllustInfo()`

- `Single GetIllustRawSize()`

- `UIIllustLayoutInfo GetIllustDefaultLayout()`

- `UIIllustLayoutInfo GetPreferredLayout()`

- `Void ResetToPreferredLayout()`

- `Boolean GetIllustRenderDetails(out, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class IllustHandler
{
	private HomeIllustView m_closure; // 0x10


	// RVA: 0x283910c VA: 0x7594e5110c
	public Void .ctor(HomeIllustView closure) { }
	// RVA: 0x283a818 VA: 0x7594e52818
	public Void ApplyIllustLayout(UIIllustLayoutInfo info) { }
	// RVA: 0x283a894 VA: 0x7594e52894
	public CharUISkinStruct GetCurSkin() { }
	// RVA: 0x283a8b0 VA: 0x7594e528b0
	public String GetIllustId() { }
	// RVA: 0x283a8cc VA: 0x7594e528cc
	public UIIllustLayoutInfo GetCurIllustInfo() { }
	// RVA: 0x283a99c VA: 0x7594e5299c
	public Single GetIllustRawSize() { }
	// RVA: 0x283aa34 VA: 0x7594e52a34
	public UIIllustLayoutInfo GetIllustDefaultLayout() { }
	// RVA: 0x283aa4c VA: 0x7594e52a4c
	public UIIllustLayoutInfo GetPreferredLayout() { }
	// RVA: 0x283aa64 VA: 0x7594e52a64
	public Void ResetToPreferredLayout() { }
	// RVA: 0x283aa7c VA: 0x7594e52a7c
	public Boolean GetIllustRenderDetails(out UICharacterIllust illust, out Camera camera) { }
}
```