# NotesWeb-jscode
  
  import { useCallback } from "react";
import styles from "./Desktop3.module.css";

const Desktop3 = () => {
  const onRectangle3Click = useCallback(() => {
    // Please sync "Desktop - 4" to the project
  }, []);

  const onUNIT1TextClick = useCallback(() => {
    // Please sync "Desktop - 4" to the project
  }, []);

  return (
    <div className={styles.desktop3}>
      <img className={styles.desktop3Child} alt="" src="../rectangle-3.svg" />
      <div className={styles.desktop3Item} />
      <div className={styles.vectorWrapper}>
        <img className={styles.vectorIcon} alt="" src="../vector.svg" />
      </div>
      <div className={styles.frameParent}>
        <div className={styles.homeWrapper}>
          <div className={styles.home}>HOME</div>
        </div>
        <div className={styles.homeWrapper}>
          <div className={styles.home}>STUDENT PROFILE</div>
        </div>
        <div className={styles.homeWrapper}>
          <div className={styles.home}>NOTES</div>
        </div>
        <div className={styles.homeWrapper}>
          <div className={styles.home}>ABOUT</div>
        </div>
      </div>
      <img className={styles.icon} alt="" src="../1787025-1@2x.png" />
      <img className={styles.maskGroupIcon} alt="" src="../mask-group@2x.png" />
      <img className={styles.vectorIcon1} alt="" src="../vector1.svg" />
      <div className={styles.welcomeUser}>WELCOME USER!!</div>
      <div className={styles.searchbar}>
        <div className={styles.searchbarChild} />
        <img className={styles.vectorIcon2} alt="" src="../vector2.svg" />
        <div className={styles.searchForNotes}>Search for notes here...</div>
      </div>
      <div className={styles.subjectName}>SUBJECT NAME</div>
      <div className={styles.desktop3Inner} onClick={onRectangle3Click} />
      <div className={styles.rectangleDiv} />
      <div className={styles.ictwotoneArrowDropDown}>
        <img className={styles.vectorIcon3} alt="" src="../vector3.svg" />
      </div>
      <div className={styles.ictwotoneArrowDropDown1}>
        <img className={styles.vectorIcon3} alt="" src="../vector3.svg" />
      </div>
      <div className={styles.ictwotoneArrowDropDown2}>
        <img className={styles.vectorIcon3} alt="" src="../vector3.svg" />
      </div>
      <div className={styles.ictwotoneArrowDropDown3}>
        <img className={styles.vectorIcon3} alt="" src="../vector3.svg" />
      </div>
      <div className={styles.desktop3Child1} />
      <div className={styles.desktop3Child2} />
      <div className={styles.desktop3Child3} />
      <div className={styles.unit1} onClick={onUNIT1TextClick}>
        <span className={styles.unit}>UNIT-</span>1
      </div>
      <div className={styles.unit4}>UNIT-4</div>
      <div className={styles.unit3}>UNIT-3</div>
      <div className={styles.unit2}>UNIT-2</div>
      <div className={styles.unit5}>UNIT-5</div>
      <div className={styles.ictwotoneArrowDropDown4}>
        <img className={styles.vectorIcon3} alt="" src="../vector3.svg" />
      </div>
    </div>
  );
};

export default Desktop3;
