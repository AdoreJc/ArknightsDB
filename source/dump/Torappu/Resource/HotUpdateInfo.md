# HotUpdateInfo

**Namespace:** `Torappu.Resource`


## Fields

- `String versionId`

- `String manifestName`

- `String manifestVersion`

- `Source source`


## Methods

- `HotUpdateInfo ShallowClone()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Resource
public class HotUpdateInfo
{
	public String versionId; // 0x10
	public ABInfo[] abInfos; // 0x18
	public String manifestName; // 0x20
	public String manifestVersion; // 0x28
	public ABInfo[] packInfos; // 0x30
	public Source source; // 0x38
	public static readonly HotUpdateInfo EMPTY; // 0x0


	// RVA: 0x373e0c8 VA: 0x7595d560c8
	public HotUpdateInfo ShallowClone() { }
	// RVA: 0x373e14c VA: 0x7595d5614c
	private Void .ctor() { }
	// RVA: 0x373e154 VA: 0x7595d56154
	private static Void .cctor() { }
}
```