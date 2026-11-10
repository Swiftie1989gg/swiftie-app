import streamlit as st

# 1. Page Configuration for Mobile
st.set_page_config(
    page_title="Swiftie Hub",
    page_icon="✨",
    layout="wide",
    initial_sidebar_state="collapsed"
)

# Custom Styling
st.markdown("""
    <style>
        .main-title { font-size: 2.2rem; font-weight: bold; color: #C8A2C8; text-align: center; }
        .sub-card { background-color: #1e1e2e; padding: 15px; border-radius: 10px; margin-bottom: 15px; }
    </style>
""", unsafe_allow_html=True)

st.markdown('<div class="main-title">✨ Swiftie News Hub ✨</div>', unsafe_allow_html=True)

# 2. Navigation Tabs
tab_news, tab_gallery, tab_stories = st.tabs(["📰 Latest News", "🖼️ Photo Gallery", "📖 Era Stories"])

# --- TAB 1: LATEST NEWS ---
with tab_news:
    st.header("Latest Taylor Swift Updates")
    
    st.subheader("💖 Philanthropy & Giving Back")
    st.write(
        "Taylor Swift and Travis Kelce recently donated a combined $26 million to 20 different charities across the U.S. "
        "The gifts supported food banks (like the Food Bank For New York City), children's hospitals, and music programs."
    )
    st.caption("Updated: November 2026")
    st.divider()

    st.subheader("🎵 Songwriters Hall of Fame")
    st.write(
        "Taylor made history with her induction into the Nashville Songwriters Hall of Fame, celebrating her decade-spanning career as a lyricist."
    )
    st.divider()

    st.subheader("🐾 New Family Member")
    st.write(
        "Taylor and Travis recently welcomed a new white Samoyed puppy into their family, who recently debuted in a Tommy Hilfiger campaign!"
    )

# --- TAB 2: PHOTO GALLERY ---
with tab_gallery:
    st.header("Photo Gallery")
    st.write("Explore featured moments from across the Eras:")
    
    col1, col2 = st.columns(2)
    
    with col1:
        st.image(
            "https://images.unsplash.com/photo-1514525253161-7a46d19cd819?w=600", 
            caption="The Concert Stage Lights"
        )
        st.image(
            "https://images.unsplash.com/photo-1511671782779-c97d3d27a1d4?w=600", 
            caption="Acoustic Performances"
        )
        
    with col2:
        st.image(
            "https://images.unsplash.com/photo-1470225620780-dba8ba36b745?w=600", 
            caption="Live Music Magic"
        )
        st.image(
            "https://images.unsplash.com/photo-1516450360452-9312f5e86fc7?w=600", 
            caption="Night Lights & Stadiums"
        )

# --- TAB 3: ERA STORIES ---
with tab_stories:
    st.header("Era Breakdown & Stories")
    
    era = st.selectbox(
        "Select an Era to read its story:",
        ["1989 (Taylor's Version)", "Folklore / Evermore", "Midnights", "The Tortured Poets Department"]
    )
    
    if era == "1989 (Taylor's Version)":
        st.subheader("🩵 1989 Era")
        st.write(
            "This era marked Taylor's full transition into synth-pop, featuring massive hits like *Blank Space* and *Style*. "
            "Re-released as *1989 (Taylor's Version)*, it includes iconic Vault tracks like *Is It Over Now?*."
        )
    elif era == "Folklore / Evermore":
        st.subheader("🌲 Folklore & Evermore")
        st.write(
            "Written and recorded during 2020, these indie-folk sister albums explored fictional storytelling, mythologies, and deep emotional acoustic landscapes."
        )
    elif era == "Midnights":
        st.subheader("🌌 Midnights Era")
        st.write(
            "A concept album detailing 13 sleepless nights scattered throughout Taylor's life, blending pop productions with introspective lyrics like *Anti-Hero*."
        )
    elif era == "The Tortured Poets Department":
        st.subheader("🤍 TTPD Era")
        st.write(
            "A double album exploring heartbreaks, fame, and personal reflections, debuting atop charts worldwide with tracks like *Fortnight* and *I Can Do It With a Broken Heart*."
        )
