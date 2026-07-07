import streamlit as st

st.set_page_config(
    page_title="Engine Oil Monitor",
    page_icon="🚗",
    layout="wide"
)

st.title("🚗 엔진오일 관리 시스템")

st.write("데이터베이스 기반 엔진오일 교체 시기 예측 시스템")

car = st.text_input("차량번호를 입력하세요")

distance = st.number_input(
    "현재 주행거리(km)",
    min_value=0,
    step=100
)

if st.button("조회"):
    st.success(f"{car} 차량을 조회했습니다.")
    st.write(f"현재 주행거리: {distance:,} km")
