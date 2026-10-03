# RugRadar

_AI-powered rug pull detection and pump potential scoring for Solana tokens_

## Summary

RugRadarはSolana上の新規トークンをオンチェーンデータから分析し、ラグプルリスクと価格上昇ポテンシャルをスコア化するダッシュボードです。機械学習モデルが流動性ロック状況、保有者分布、取引パターンなどを学習し、トレーダーに実用的なリスク・リワード指標を提供します。

## Target users

Solana memecoin and new token traders

## Problem

新規トークンの多くがラグプルで、トレーダーは手作業でオンチェーンデータを調べる時間がなく判断を誤りやすい。

## Solution

オンチェーンデータを自動収集し機械学習でリスクスコアと上昇ポテンシャルスコアを算出、ワンクリックで確認できるダッシュボードを提供する。

## MVP features

- 新規トークンのリアルタイムスキャンとリスクスコア表示
- 流動性ロック・保有者集中度・コントラクト権限の自動チェック
- 過去の値動きパターンから学習した上昇確率予測モデル
- 危険トークン検知時のアラート通知（Discord/Telegram連携）
- トークン比較ビューでリスク・リワードを一目で確認

## Chains

Solana

## Tech

Solana RPC/Geyser, Python, scikit-learn/XGBoost, PostgreSQL, React, Helius API, Discord Webhook

## Category

AI

## Why now

Solanaでのミームコイン発行が爆発的に増加し、ラグプル被害が深刻化しているため、自動検知ツールの需要が急増している。

## Roadmap

- 学習データセットの拡充とモデル精度向上
- ウォレット分析による詐欺師の再犯検知機能追加
- トークン課金制API提供とTelegramボット展開
