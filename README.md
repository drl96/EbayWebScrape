# Ebay Web Scraping Script:

## Technologies Used:

Python, Jupyter Notebook, Beautiful Soup, pandas

## Description:

This script uses Beautiful Soup to scrape the following data from ebay.com search results:

- Product name
- Product condition
- Product price

The data is then exported from a pandas DataFrame to a csv file

## Sample Output:

Below is the scraped data from the [ebay search 'mouse'](https://www.ebay.com/sch/i.html?_from=R40&_trksid=p2334524.m570.l1313.TR12.TRC2.A0.H0.Xmouse.TRS0&_nkw=mouse&_sacat=0&LH_TitleDesc=0&_osacat=0&_odkw=laptop)
| Product Name                                                                     | Product Condition | Product Price    |
|----------------------------------------------------------------------------------|-------------------|------------------|
| 2.4GHz High Quality Wireless Optical Mouse/Mice + USB 2.0 Receiver for PC Laptop | Brand New         | $7.99 to $12.99  |
| Wireless USB Optical Mice Gaming Mouse 7 Color LED Backlit Rechargeable For PC   | Brand New         | $10.97           |
| 2.4GHz Wireless Optical Mouse Mice & USB Receiver For PC Laptop Computer DPI USA | Brand New         | $7.89            |
| 2.4GHz USB Wireless Optical Mouse Mice for Apple Mac Macbook Pro Air PC White    | Brand New         | $6.95            |
| 2.4GHz 2400 DPI Wireless Optical Mouse Mice + USB Receiver for PC Laptop MAC     | Brand New         | $12.98           |
| 2.4GHz Cordless Wireless Optical Mouse Mice For Laptop PC Computer  4 colors US  | Brand New         | $6.16            |
| HP X3000 Wireless Mouse (H2C22AA#ABL)                                            | Brand New         | $12.49           |
| 2.4GHz Wireless Optical Mouse Adjustable DPI Cordless Mice + Receiver for Laptop | Brand New         | $6.99            |
| Philips SPK7214 USB Wired Computer Mouse for PC Laptop Desktop Computers         | Brand New         | $6.99            |
| Wired USB Optical Mouse Wireless Optical Mouse Retractable Mini USB Mouse For PC | Brand New         | $4.99 to $7.99   |
| Wireless 7 Color Backlit Light Rechargeable Silent USB Optical Mice Gaming Mouse | Brand New         | $10.97           |
| 2.4GHz Wireless Optical Mouse Mice & USB Receiver For PC Laptop Computer DPI USA | Brand New         | $6.99            |
| "JETech M2260 Bluetooth Wireless Mouse for PC, Mac, and Android OS Tablet "      | Brand New         | $7.99            |
| 2.4GHz Wireless Optical Mouse &USB Receiver Adjustable DPI for PC Laptop Desktop | Brand New         | $6.75            |
| 2.4GHz Wireless Optical Mouse Mice & USB Receiver For PC Laptop Computer DPI USA | Brand New         | $1.69            |
| Apple Magic Mouse 2 Charging Dock                                                | Brand New         | $9.00 to $18.00  |
| VicTsing 2.4G Wireless Ergonomic Mouse 6 Button 2400DPI Mice For PC Laptop Mac   | Brand New         | $11.99           |
| Gaming Mouse 3 Button USB Wired LED Breathing Fire Button 3200 DPI Laptop PC USA | Brand New         | $7.69            |
| Wireless Optical Gaming Mouse Rechargeable Mice + USB Receiver for PC Laptop     | Brand New         | $10.88           |
| Logitech M325 Wireless Mouse with unifying receiver for PC Mac                   | Refurbished       | $12.98           |
| 2.4GHz Wireless Cordless Optical Gaming Mouse Mice + USB Receiver for PC Laptop  | Brand New         | $9.19            |
| 2.4GHz Cordless Wireless Optical Mouse Mice For Laptop PC Computer  4 colors USA | Brand New         | $6.08            |
| Brand NEW--Logitech B100 3-Button USB Wired Optical Scroll Mouse (BLACK)         | Brand New         | $8.80            |
| 2.4GHz Wireless Mouse Optical Mice Rechargeable Cordless For Macbook Pro Laptop  | Brand New         | $9.47 to $9.97   |
| Lenovo Wireless Mouse Black                                                      | Brand New         | $12.99           |
| USB 2.0 Optical Wired Scroll Wheel Mouse Mice for PC Laptop Notebook Desktop Red | Brand New         | $5.99            |
| Logitech M170 Wireless Mouse 2.4 GHz For Laptop Macbook PC US STOCK  FAST SHIP   | Brand New         | $10.59 to $10.79 |
| VicTsing 2.4GHz 2.4G Wireless Optical Mouse 2400DPI Adjustable 6 Buttons  US     | Brand New         | $10.99           |
| Logitech M325c Wireless Mouse w/nano receiver for PC Mac                         | Refurbished       | $10.99           |
| Logitech G305 LIGHTSPEED Wireless Gaming Mouse Black                             | Refurbished       | $35.95           |
| Ergonomic USB Wired Mouse 2400DPI RGB Flowing LED Optical Gaming Mice PC Laptop  | Brand New         | $11.69           |
| HP X1500 Wired Mouse \| Black; Metallic Gray \| H4K66AA                          | Brand New         | $10.99           |
| 2.4GHz Wireless DPI Cordless Optical Mouse Mice USB Receiver For PC Laptop RED   | Brand New         | $6.15            |
| Generic Mini USB Mouse Black and Silver 2 Button 2.4ghz 1000 dpi Ergonomic New!  | Brand New         | $4.99            |
| MLA02LL/A VG Apple Wireless Magic Mouse 2 Bluetooth Rechargeable                 | Brand New         | $22.99           |
| Lenovo Wired USB Mouse                                                           | Brand New         | $7.99            |
| Hype 2.4GHz Wireless Optical Mouse W/Hidden Nano USB Receiver Purple New         | Brand New         | $8.99            |
| 2.4GHz Wireless DPI Cordless Optical Mouse Mice USB Receiver For PC Laptop Blue  | Brand New         | $6.15            |
| Logitech M325c Wireless Compact Size Optical Mouse for Computer Windows Mac OS   | Brand New         | $14.99           |
| Gaming Mouse LED Breathing Fire 4 Button Silent USB Wired 1600 DPI Laptop PC USA | Brand New         | $7.99 to $8.99   |
| ❗️Apple Magic Mouse 2 ❗️Wireless Rechargeable - Brand New - Silver - MLA02LL/A   | Brand New         | $62.99           |
| 1600DPI Wireless Gaming Mouse LED Optical Mice Mute Rechargeable for PC Laptop   | Brand New         | $12.99           |
| Logitech M325C Party Collection Wireless Optical Mouse - Yellow Zigzag           | Brand New         | $12.49           |
| Bluetooth Wireless Mouse Computer Optical Mice for PC Mac Android OS Tablets LU  | Brand New         | $12.19           |
| HOT 2.4Ghz Wireless USB car mouse Cordless Optical LED Laptop PC Laptop MAC Mice | Brand New         | $11.99 to $12.75 |
| 2.4GHz Wireless Cordless Mice Optical Mouse for PC Laptop Receiver Grey w/ pad   | Brand New         | $6.15            |
| Logitech Wireless Mouse M325 Celebration Mini Mint                               | Pre-Owned         | $11.73           |
| X8 Super Quiet Wireless Gaming Mouse LED Backlit USB Rechargeable Optical NEW    | Brand New         | $10.88           |
| High Quality Wireless Optical Gaming Mouse 2.4ghz 2400dpi for PC/Laptop/Mac      | Brand New         | $8.99            |
| NEW Genuine HP USB Optical Mouse 672652-001 Black Wired - 2 Button Scroll        | Brand New         | $10.95           |
| Razer DeathAdder Essential - Optical Esports Gaming Mouse-Wired                  | Brand New         | $29.95           |
| "HP x3000 Wireless Mouse, Black (H2C22AA#ABL)"                                   | Brand New         | $13.29           |
| Logitech G602 Wireless Gaming Mouse PC and Mac 250 Hour Battery Life             | Open Box          | $24.99           |
| HP Wireless Mouse 200 \| Black \| X6W31AA#ABL                                    | Brand New         | $15.55           |
| Logitech M317c Wireless Mouse for PC and Mac Nano Receiver                       | Refurbished       | $9.99            |
| PHILIPS SPK9304 Gaming Mouse RGB 7-Color Breathing Wired Optical Mouse Sensor    | Brand New         | $9.99            |
| Logitech G203 Prodigy RGB Wired Gaming Mouse                                     | Pre-Owned         | $21.99           |
| Wireless Bluetooth Mouse Cordless Dual Mouse Portable Ergonomic for Laptop PC    | Brand New         | $10.99           |
| Wireless Optical Mouse 2.4GHz Quality Mice USB 2.0 Receiver for PC Laptop BLUE   | Brand New         | $5.99            |
| Logitech M100 3-Button USB Optical Wired Scroll Mouse  (Gray)-FREE SHIPPING      | Brand New         | $9.99            |
| Anker 2.4G Wireless Vertical Ergonomic Optical Mouse 800/1200/1600 DPI 5 Buttons | Brand New         | $22.99           |
| iClever Vertical Mouse - Ergonomic Mouse Wireless 6 Buttons with Adjustable DPI  | Open Box          | $9.99            |
| USB Wired Gaming Mouse 6 Button Optical Mice 1600 DPI 7 Color LED For PC Laptop  | Brand New         | $14.97           |
