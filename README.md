# Awesome-Hotends
A collection of 3D printer hotends.

The 3D printer hotend is the business end of FDM 3D printers, responsible for melting plastic from a solid to a molten state.

This is a list of popular all-metal hotends compatible with common toolheads for Voron pritner, Printers for Ants, and other custom 3D printers. Non-standardized, PTFE lined, or proprietary hotends for  prebuilt machines shall typically be excluded unless widely adopted and supported by the community.

Disclaimer: The listed flow rates for the hotends are estimated claims and will vary best on test conditions.

Looking for a toolhead to go with your hotend of choice? Check out [Awesome-Toolheads](https://github.com/SartorialGrunt0/Awesome-Toolheads).

How about an extruder? Checkout [Awesome-Extruders](https://github.com/SartorialGrunt0/Awesome-Extruders).

--------------------

## Table of contents
- [Standard Flow](#standard-flow)
- [High Flow](#high-flow)
- [Ultra High Flow](#ultra-high-flow)
- [Legacy](#legacy)

--------------------

### Standard Flow (SF)

Standard flow hotends are best suited for slower machines where higher flow hotends may lead to heat creep or are unneccessary. They typically have a max flow rate under 15 mm3/s. Many standard flow hotends can move into the high-flow category with meltzone extensions and CHT/filament split nozzles.

- [E3D V6](https://e3d-online.com/products/v6-all-metal-hotend?srsltid=AfmBOorJ2wINp7xIatb-pjD3N5__TxmlyD4AZizJTsQ42wTN5GP8wUt0) - The OG hotend, supports V6 groove mount, V6 nozzles, max flow~12 mm3/s.
- [E3D Revo](https://e3d-online.com/pages/revo-configurator?srsltid=AfmBOoqULDtDqrSKdaeUmanreH3cyC_Ivq-s62-Zx9CbucDiJVMmh_cF) - The new and improved V6 hotend, has variants for V6 groove mount and Voron mount, features a quick cold swap nozzles, ceramic heater, max flow~12 mm3/s.
- [E3D Panda Revo](https://biqu.equipment/products/biqu-panda-hotend?_pos=2&_sid=31629afe3&_ss=r&variant=40464525492322) - Variant of E3D revo, supports Bambu mounting.
- [Phateus Dragon SF](https://www.phaetus.com/en-us/products/dragon-hotend-st) - V6 style hotend, introduced dragon mounting, one-handed nozzle changes, max flow~15 mm3/s.
- [Phateus Dragonfly](https://www.phaetus.com/en-us/products/dragonfly-hotend-bms) - V6/Ender style hotend, supports groove or Ender mounting, max flow~15mm3/s
- [Trianglelabs CHC](https://trianglelab.net/products/tchc-td6s-hotend?VariantsId=10379) - V6 style hotend, supports groove mount, ceramic heater, single or two-piece nozzle and throat.
- [Mellow NF Crazy](https://3dmellow.com/products/nf-crazy-v2-hotend?VariantsId=10201) - Ender style hotend, support Ender or V6 mounting, V6 or V6 Volcano Nozzles, one-handed nozzle changes.

--------------------

### High Flow (HF)

High flow hotends are the most common type of hotend used today. They provide a balance of flow rate, standard nozzles, and size. They typically have a max flow rate under 25 mm3/s.

- [Phateus Rapido](https://www.phaetus.com/en-us/products/rapido-hotend) - V6 style hotend, supports groove or Dragon mounting, thermocouples, one-handed nozzle changes, max flow~25 mm3/s, more with UHF adapter.
- [Phateus Dragon HF](https://www.phaetus.com/en-us/products/dragon-hotend-hf) - V6 style hotend, supports groove or Dragon mount, one handed nozzle changes, max flow~22 mm3/s.
- [Dragonfly HIC](https://www.phaetus.com/en-us/products/drangonfly-hotend-hic) - Ender style hotend, support Ender mounting, Volcano style nozzles.
- Red Lizard K1- V6 style hotend, clone of Dragon HF, supports groove or Dragon mounting, one handed nozzle changes, max flow~22 mm3/s.
- [Bambulabs X1/P1](https://us.store.bambulab.com/products/bambu-hotend-x1c?srsltid=AfmBOor9iFEZMLme1fWw1Gn_TYon7LnDEz7TjBWHEQlGLeKTR-k40Axx) - Bambulabs hotend, supports X1/P1 style mounting, festures a low price, max flow~22 mm3/s.
- [TZ 2.0](https://trianglelab.net/products/tz-20-hotend-for-bambu-lab-x1-p1p?VariantsId=11766) - Clone hotend with Bambulabs style heater block, availabe in a Bambulabs, V6+Dragon, or Ender style heatbreak and mounting, feautures V6 nozzles, one handed nozzle changes, Max flow~22 mm3/s.
- [TZ 3.0/4.0](https://www.trianglelab.net/products/tz-40-hotend?VariantsId=12040) - Clone hotend with Bambulabs style heater block, variant of TZ 2.0, available in a Bambulabs, V6+Dragon, or Ender style heatbreak and mounting, feautures single-piece throat+nozzle design, one handed nozzle changes.
- [CHC Pro](https://trianglelab.net/products/chc-pro-hotend?VariantsId=10274) - V6 style hotend, supports groove mount, ceramic heater, variant of CHC hotend with extended ceramic heater.

--------------------

### Ultra High Flow

Ultra hign flow hotends are reserved for the fastest most demanding machines. They offer flow rates in the ranges of 30-50 mm3/s at the cost of heat creep, size, and sometimes non-standard nozzles.

- [Rapido Plus](https://www.phaetus.com/en-us/products/rapido-plus-hotend) - V6 style hotend, variant of Rapido, supports groove or Dragon mounting, thermocouples, ceramic heater, one handed nozzle changes.
- [Mellow Fluxheat](https://www.aliexpress.us/item/3256809993234845.html?spm=a2g0o.productlist.main.1.5cf8lhtRlhtRQW&algo_pvid=5e05c10c-31e8-4768-bc6f-75312ab4e6dc&algo_exp_id=5e05c10c-31e8-4768-bc6f-75312ab4e6dc-0&pdp_ext_f=%7B%22order%22%3A%22126%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%2112.00%215.64%21%21%2112.00%215.64%21%402101c59117729179986226184ebede%2112000051421128508%21sea%21US%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3Af793c4b1%3Bm03_new_user%3A-29895&curPageLogUid=jZXIIOnETKy8&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005010179549597%7C_p_origin_prod%3A) - V6 or Bambu style hotend, Dragon or Bambu mounting, one handed nozzle changes, support for an integrated nozzle probe, V6 nozzles.
- [Mellow Heatcore](https://3dmellow.com/products/mellow-heatcore-4-uhf-alps-hotend-smart-leveling-nozzle-probe-for-voron-blv-vzbot-hevort-diy-3d-printer-high-flow-and-high-speed) - V6 style hotend, Dragon mounting, one handed nozzle changes, support for an integrated nozzle probe, V6 nozzles.
- [Phaetus Conch](https://www.phaetus.com/en-us/products/conch-hotend%E2%84%A2-m6-x1-p1-series) - Hotend in Bambulabs or AD5M style, ceramic heater, one-handed nozzle changes, V6 nozzles.
- [Dragon UHF](https://www.phaetus.com/en-us/products/dragon-hotend-%C2%AE-uhf) - V6 style hotend, variant of Dragon HF, supports groove or Dragon mounting, ceramic heater, one handed nozzles changes.
- [Trianglelabs Dragon Ace](https://www.phaetus.com/en-us/products/dragon-hotend-%C2%AE-uhf) - V6 style hotend, variant of Dragon UHF, supports groove or Dragon mount, ceramic heater, thermocouples, V6 nozzles.
- [Trianglelabs Dragon Ace Volcano](https://www.phaetus.com/en-us/products/dragon-hotend-%C2%AE-uhf) - V6 style hotend, variant of Dragon UHF, supports groove or Dragon mount, ceramic heater, thermocouples, V6 Volcano nozzles.
- Red Lizard K1 HF
- [CHC XL](https://shop.thevirtualfoundry.com/products/chc-xl-extreme-high-flow-hot-end-wear-resistant-air-or-water-cooled?variant=47412803698933&country=US&currency=USD&otto_prod=67659&dm_cam=22855725992&dm_grp=&dm_ad=&dm_kw=&dm_net=adwords&tw_source=google&tw_adid=&tw_campaign=22855725992&tw_kwdid=&utm_term=&utm_campaign=WINNER-2++Performance+Max-+Aug-1+-+Generated+by+Merchants.google.com&utm_source=adwords&utm_medium=ppc&hsa_acc=4779942964&hsa_cam=22855725992&hsa_grp=&hsa_ad=&hsa_src=x&hsa_tgt=&hsa_kw=&hsa_mt=&hsa_net=adwords&hsa_ver=3&gad_source=1&gad_campaignid=22878784281&gbraid=0AAAAArDmf6Rwv2oG5zW85S38-BWkKCdyi&gclid=CjwKCAiAkbbMBhB2EiwANbxtbUHgUy_5TGMF57ytS22KjhK-iM87KNdyLdaQcECuy0y3I_wmW6KHuRoCpboQAvD_BwE) - V6 style hotend, supports dragon mounting, ceramic heaters, water or air cooling.
- [Goliath](https://github.com/VzBoT3D/Goliath) - V6 style hotend, supports dragon mounting, nichrome wire heater, thermocouples, water or air cooling.

--------------------

Did I miss something? Open an issue and I'll consider adding it to the list.
