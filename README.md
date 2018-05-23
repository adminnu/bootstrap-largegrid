# bootstrap-largegrid
Bootstrap 4 CSS Grid addition for big and retina screens coverage.

<table class="table table-bordered table-striped">
            <thead>
              <tr>
                <th></th>
                <th>
                  HD+
                  <small>≥1600px</small>
                </th>
                <th>
                  Full HD 1080p
                  <small>≥1920px</small>
                </th>
                <th>
                  Retina 1440p
                  <small>≥2560px</small>
                </th>
                <th>
                  15" Retina
                  <small>≥2880px</small>
                </th>
                <th>
                  UHD
                  <small>≥3840px</small>
                </th>
                <th>
                  4K
                  <small>≥4096px</small>
                </th>
                <th>
                  8K
                  <small>≥8192px</small>
                </th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <th>Grid behavior</th>
                <td colspan="7">Collapsed to start, horizontal above breakpoints</td>
              </tr>
<!--
              <tr>
                <th>Max container width</th>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
              </tr>
-->
              <tr>
                <th>Class prefix</th>
                <td><code>.col-xga-</code></td>
                <td><code>.col-fhd-</code></td>
                <td><code>.col-rt-</code></td>
                <td><code>.col-rt15-</code></td>
                <td><code>.col-uhd-</code></td>
                <td><code>.col-4k-</code></td>
                <td><code>.col-8k-</code></td>
              </tr>
              <tr>
                <th># of columns</th>
                <td colspan="7">12</td>
              </tr>
<!--
              <tr>
                <th>Max column width</th>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
              </tr>
-->
              <tr>
                <th>Gutter width</th>
                <td colspan="7">30px (15px on each side of a column)</td>
              </tr>
              <tr>
                <th>Nestable</th>
                <td colspan="7">Yes</td>
              </tr>
              <tr>
                <th>Offsets</th>
                <td colspan="7">Yes</td>
              </tr>
              <tr>
                <th>Column ordering</th>
                <td colspan="7">Yes</td>
              </tr>
            </tbody>
          </table>

## Extends Bootstrap v4 by:
* Adding col-xga (1600+), col-fhd (1920+), col-rt (2560+), col-rt15 (2880+), col-uhd (3840+), col-4k (4096+), col-8k (8192+) classes with all related options: order, offser
* Adding options none, inline, inline-block, block, table, table-row, table-cell, flex, inline-flex for all three
* Adding options flex-*, justify-content-*, align-items-*, align-content-*, align-self* for all three

## Installation
### Basic
Simply include bootstrap-largegrid.min.css file in header, after bootstrap.min.css and before your own CSS styles.

## Other
* MIT license, so use, modify and improve as you wish
* Fork & Pull requests are welcome
* Will be glad to hear about projects you have used this on
* Enjoy
