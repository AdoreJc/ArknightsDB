# ResourceManagerMediator

**Namespace:** ` `


## Fields

- `ResourceManager _rm`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
internal class ResourceManagerMediator
{
	private ResourceManager _rm; // 0x10

	internal String ModuleDir { get; }
	internal Type LocationInfo { get; }
	internal Type UserResourceSet { get; }
	internal String BaseNameField { get; }
	internal CultureInfo NeutralResourcesCulture { get; }
	internal Boolean LookedForSatelliteContractVersion { get; set; }
	internal Version SatelliteContractVersion { get; set; }
	internal UltimateResourceFallbackLocation FallbackLoc { get; }
	internal RuntimeAssembly CallingAssembly { get; }
	internal RuntimeAssembly MainAssembly { get; }
	internal String BaseName { get; }

	// RVA: 0x5fdf350 VA: 0x75985f7350
	internal Void .ctor(ResourceManager rm) { }
	// RVA: 0x5fdf3d0 VA: 0x75985f73d0
	internal String get_ModuleDir() { }
	// RVA: 0x5fdf3ec VA: 0x75985f73ec
	internal Type get_LocationInfo() { }
	// RVA: 0x5fdf408 VA: 0x75985f7408
	internal Type get_UserResourceSet() { }
	// RVA: 0x5fdf424 VA: 0x75985f7424
	internal String get_BaseNameField() { }
	// RVA: 0x5fdf440 VA: 0x75985f7440
	internal CultureInfo get_NeutralResourcesCulture() { }
	// RVA: 0x5fdf45c VA: 0x75985f745c
	internal String GetResourceFileName(CultureInfo culture) { }
	// RVA: 0x5fdf47c VA: 0x75985f747c
	internal Boolean get_LookedForSatelliteContractVersion() { }
	// RVA: 0x5fdf498 VA: 0x75985f7498
	internal Void set_LookedForSatelliteContractVersion(Boolean value) { }
	// RVA: 0x5fdf4b8 VA: 0x75985f74b8
	internal Version get_SatelliteContractVersion() { }
	// RVA: 0x5fdf4d4 VA: 0x75985f74d4
	internal Void set_SatelliteContractVersion(Version value) { }
	// RVA: 0x5fdf4f0 VA: 0x75985f74f0
	internal Version ObtainSatelliteContractVersion(Assembly a) { }
	// RVA: 0x5fdf548 VA: 0x75985f7548
	internal UltimateResourceFallbackLocation get_FallbackLoc() { }
	// RVA: 0x5fdf564 VA: 0x75985f7564
	internal RuntimeAssembly get_CallingAssembly() { }
	// RVA: 0x5fdf580 VA: 0x75985f7580
	internal RuntimeAssembly get_MainAssembly() { }
	// RVA: 0x5fdf604 VA: 0x75985f7604
	internal String get_BaseName() { }
}
```