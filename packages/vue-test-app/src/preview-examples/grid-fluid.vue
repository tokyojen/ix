<!--
 * SPDX-FileCopyrightText: 2023 Siemens AG
 *
 * SPDX-License-Identifier: MIT
 *
 * This source code is licensed under the MIT license found in the
 * LICENSE file in the root directory of this source tree.
-->

<script setup lang="ts">
import { IxCol, IxGrid, IxRow } from '@siemens/ix-vue';
// Example styling for documentation
import './grid.css';
</script>

<template>
  <div class="example-parent">
    <h4>Non fluid (default)</h4>
    <IxGrid>
      <IxRow>
        <IxCol>1</IxCol>
        <IxCol>2</IxCol>
        <IxCol>3</IxCol>
        <IxCol>4</IxCol>
        <IxCol>5</IxCol>
        <IxCol>6</IxCol>
        <IxCol>7</IxCol>
        <IxCol>8</IxCol>
        <IxCol>9</IxCol>
        <IxCol>10</IxCol>
        <IxCol>11</IxCol>
        <IxCol>12</IxCol>
      </IxRow>
    </IxGrid>

    <h4>fluid</h4>
    <IxGrid fluid>
      <IxRow>
        <IxCol>1</IxCol>
        <IxCol>2</IxCol>
        <IxCol>3</IxCol>
        <IxCol>4</IxCol>
        <IxCol>5</IxCol>
        <IxCol>6</IxCol>
        <IxCol>7</IxCol>
        <IxCol>8</IxCol>
        <IxCol>9</IxCol>
        <IxCol>10</IxCol>
        <IxCol>11</IxCol>
        <IxCol>12</IxCol>
      </IxRow>
    </IxGrid>
  </div>
</template>

